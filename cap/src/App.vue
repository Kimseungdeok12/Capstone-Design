<template id="app">
  <div>
    <Header-nav />
  </div>

<main>

  <Main-carousel />

  <Mainintroduce/>

</main>
  

<Footermain/>


</template> 
 
<script>
  import HeaderNav from './components/Header-nav.vue';
  import MainCarousel from './components/Main-carousel.vue';
  import Footermain from './components/Footer-footer.vue';
  import Mainintroduce from './components/Main-introduce.vue';

  export default {
    name: 'App',
    components: {
      HeaderNav,
      MainCarousel,
      Footermain,
      Mainintroduce
    },
  };
</script>
 
<style>
    
  </style>