<template>
  <nuxt-child />
</template>

<style>
  .posts {
    display: flex;
    align-items: center;
    flex-direction: column;
  }

  .posts h1 {
    padding: 20px;
  }

  .posts a {
    text-decoration: none;
    color: black
  }

  .posts a:hover,
  .posts a:active {
    color: grey;
  }
</style>