<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="logo DC"> 
    <nav>
        <ul class="nav justify-content-center my-3">
            <li class="nav-item" v-for="(link, index) in menu" :key="index">
                <a class="nav-link" :href="link.url" :class="{ 'active': link.current }"> {{ link.text }}</a>
            </li>
        </ul>
    </nav>
  </header>
</template>

<script>
  export default {
    name: 'HeaderApp',
    data() {
      return {
        menu: [
          {
            text: "Characters",
            url: "#",
            current: false,
          },
          {
            text: "Comics",
            url: "#",
            current: true,
          },
          {
            text: "Movies",
            url: "#",
            current: false,
          },
          {
            text: "Tv",
            url: "#",
            current: false,
          },
          {
            text: "Games",
            url: "#",
            current: false,
          },
          {
            text: "Collectibles",
            url: "#",
            current: false,
          },
          {
            text: "Videos",
            url: "#",
            current: false,
          },
          {
            text: "Fans",
            url: "#",
            current: false,
          },
          {
            text: "News",
            url: "#",
            current: false,
          },
          {
            text: "Shop",
            url: "#",
            current: false,
          },
        ]

      }
    }
    
  }
</script>

<style lang="css" scoped>

</style>