<template>
  <li>
    <nuxt-link :to="'/posts/' + id" class="post-title">{{ title }}</nuxt-link>
    <p>{{ previewText }}</p>
  </li>
</template>

<script>
export default {
  name: 'PostPreview',
  props: {
    id: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    },
    previewText: {
      type: String,
      required: true
    },
    contentText: {
       type: String,
      required: true
    }
  }
}
</script>

<style scoped>
  .post-title {
    font-weight: 600;
    font-size: 2.5vh;
  }
</style>
