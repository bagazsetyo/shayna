<template>
  <div class="home">
     <Headershayna />
     <HeroCarousel />
     <Banner />
     <Insta />
     <LogoPartner />
     <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Headershayna from '@/components/Headershayna.vue'
import HeroCarousel from '@/components/HeroCarousel.vue'
import Banner from '@/components/Banner.vue'
import Insta from '@/components/Insta.vue'
import LogoPartner from '@/components/LogoPartner.vue'
import Footer from '@/components/Footer.vue'

// import carousel from 'vue-owl-carousel'


export default {
  name: 'Home',
  components: {
    Headershayna,
    HeroCarousel,
    Banner,
    Insta,
    LogoPartner,
    Footer
    // carousel
  }
}
</script>
