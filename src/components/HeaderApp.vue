<template>
  <header class="container">
    <div class="row">
      <div class="col-sm-3">
        <img src="../assets/img/dc-logo.png" alt="logo DC" class="logo">
      </div>
      
      <ul class="nav justify-content-center my-3 col-sm-9 items">
        <li class="nav-item" v-for="(link, index) in menu" :key="index">
        <a class="nav-link" :href="link.url" :class="{ 'active': link.current }"> {{ link.text }}</a>
        </li>
      </ul>
      
    </div>
     
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
.logo{
  height: 100px;
  padding:10px;
}

header li{
  display: inline-block;
  text-transform: uppercase ;
  padding: 10px;
}

header{
  font-family: 'Open Sans', sans-serif;
}

li a{
  color: gray;
}


</style>