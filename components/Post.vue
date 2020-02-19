<template>
  <div class="container">
    <h1>{{ title }}</h1>
    <div class="post-details">
      <p>Last updated on {{ lastUpdated }}</p>
      <p>Written by {{ name }}</p>
    </div>
    <p class="post-content">{{ contentText }}</p>
  </div>
</template>

<script>
export default {
  name: 'Post',
  props: {
    id: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    },
    name: {
      type: String,
      required: true
    },
    contentText: {
      type: String,
      required: true
    },
    lastUpdated: {
      type: Date,
      required: true
    }
  }
}
</script>

<style scoped>
  .post-content {
    width: 70%;
  }
</style>