<template>
  <h1 class="red">{{ title }}</h1>
</template>
<script>
  export default {
    data() {
      return {
        title: "Page d'accueil"
      }
    },
    head() {
      return {
        title: this.title,
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: "Description de la page d'accueil"
          }
        ]
      }
    }
  }
</script>

<style>
  .red {
    color: red;
  }
</style>