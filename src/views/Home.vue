<template>
  <div class="home">
      <HeaderShayna />
      <SlideHero />


  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import SlideHero from '@/components/SlideHero.vue'
//import carousel from 'vue-owl-carousel'
export default {
  name: 'Home',
  components: {
    HeaderShayna,
    SlideHero,
    //carousel
  }
}
</script>
