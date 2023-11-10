<template>
  <main>
    <div class="jumbotron">
        <div class="container ">
            <span class="btn">CURRENT SERIES</span>
        </div>
    </div>
    <section class="container">
            <div class="row gy-2">
                <div class="col-12 col-md-4 col-lg-3" v-for="(comic, index) in comix" :key="index">
                    <CardComponent :image="comic.thumb" :title="comic.series" />
                </div>
            </div>
    </section>

  </main>
</template>

<script>
import { comics } from '../data/comics.js';
import CardComponent from './CardComponent.vue';

  export default {
    name: 'MainContentApp',
    components: {
      CardComponent
    },
    data (){
      return{
        comix: comics 
      };
    }
    
  }
</script>

<style lang="css" scoped>
main{
  background-color: black;
  color: white;
  font-family: 'Open Sans', sans-serif;
}

.jumbotron{
  background-image: url('../assets/img/jumbotron.jpg');
  height: 500px;
  width: 100%;
}

</style>