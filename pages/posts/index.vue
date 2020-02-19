<template>
  <div class="container">
    <h1>This is the posts page</h1>
    <h3>Please select a post that you would like to see</h3>
    <ul>
      <li><nuxt-link :to="'/posts/' + 1">Post title</nuxt-link></li>
    </ul>
    <nuxt-link to="/posts/new" class="new-post">Add a new post</nuxt-link>
  </div>
</template>

<style scoped>
  .new-post {
    padding: 10px;
    margin: 10px;
    background-color: lightgray;
    border-radius: 2%;
    border: 1px solid black;
  }
</style>

