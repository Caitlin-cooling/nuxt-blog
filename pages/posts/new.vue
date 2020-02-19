<template>
  <div class="container">
    <h1>Add a new post</h1>
    <textarea></textarea>
    <button @click="handleCreatePost">Create post</button>
  </div>
</template>

<script>
export default {
  methods: {
    handleCreatePost() {
      this.$router.push('/posts/confirmation')
    }
  }
}
</script>