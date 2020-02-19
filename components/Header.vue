<template>
  <header class="header">
    <ul class="list">
      <li><nuxt-link to="/">Home</nuxt-link></li>
      <li><nuxt-link to="/about">About</nuxt-link></li>
      <li><nuxt-link to="/admin">Admin</nuxt-link></li>
      <li><nuxt-link to="/posts">Posts</nuxt-link></li>
    </ul>
  </header>
</template>

<style scoped>
  .header {
    display: flex;
    width: 100%;
    height: 80px;
    align-items: center;
    justify-content: center;
    background-color: bisque;
  }

  .list {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 80%;
  }
</style>