<script>
export default {
  name: "AppHeader",
  data() {
    return {
      menuLinks: [
        {
          text: "CHARACTHERS",
          url: "#"
        },
        {
          text: "COMICS",
          url: "#"
        },
        {
          text: "MOVIES",
          url: "#"
        },
        {
          text: "TV",
          url: "#"
        },
        {
          text: "GAMES",
          url: "#"
        },
        {
          text: "COLLECTIBLES",
          url: "#"
        },
        {
          text: "VIDEOS",
          url: "#"
        },
        {
          text: "FANS",
          url: "#"
        },
        {
          text: "NEWS",
          url: "#"
        },
        {
          text: "SHOP",
          url: "#"
        },

      ]

    }
  }
}
</script>


<template>
  <header class="d-flex container justify-content-between">
    <img class="mt-4" src="../assets/img/dc-logo.png" alt="">
    <nav class="d-flex align-items-center">
      <a class="px-3" v-for="link in menuLinks" :href="link.url"> {{ link.text }}</a>
    </nav>
  </header>
</template>


<style scoped>
a {
  text-decoration: none;
  font-size: 12px;
  font-weight: 800;
  color: #474646;
}
</style>