<template>
  <div class="home">
      <HeaderShayna />
      <SlideHero />
      <ProductSlide />
      <InstaShayna />
      <PartnerLogo />
      <FooterShayna />


  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderShayna.vue'
import SlideHero from '@/components/SlideHero.vue'
import ProductSlide from '@/components/ProductSlide.vue'
import InstaShayna from '@/components/InstaShayna.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import FooterShayna from '@/components/FooterShayna.vue'
//import carousel from 'vue-owl-carousel'
export default {
  name: 'Home',
  components: {
    HeaderShayna,
    SlideHero,
    ProductSlide,
    InstaShayna,
    PartnerLogo,
    FooterShayna
    //carousel
  }
}
</script>
