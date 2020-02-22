<template lang="pug">
  div.pug
    ul
      li(v-for="user in users")
        a: h1(v-bind:class="user.favouriteColour") Hello {{ user.name }}
        p(class="pug__p" v-if="user.message") {{ user.message }}
</template>

<script>
export default {
  data: function () {
    return  {
      users: [
        {
          name: 'Caitlin',
          message: 'How are you today?',
          favouriteColour: 'blue'
        },
        {
          name: 'Leanne',
          message: 'Good morning',
          favouriteColour: 'green'
        }
      ]
    }
  }
}
</script>

<style scoped>
  .pug__p {
    margin: 20px;
  }

  .blue {
    color: blue;
  }

  .green {
    color: green;
  }
</style>