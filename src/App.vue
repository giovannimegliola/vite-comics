<template>

  <HeaderApp />

  <MainContentApp />
  
  <FooterApp />

</template>

<script>
import HeaderApp from './components/HeaderApp.vue';
import MainContentApp from './components/MainContentApp.vue';
import FooterApp from './components/FooterApp.vue';
export default {
  name: 'App',
  components: {
    HeaderApp,
    MainContentApp,
    FooterApp
  },
  data(){
    

    return {}
  }
}
</script>

<style lang="css" scoped>

</style>
