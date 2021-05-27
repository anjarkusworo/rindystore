<template>
  <div class="home">
    <Header/>
    <Carousel/>
    <ItemsBanner/>
    <InstaGallery />
    <PartnerLogo />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import Header from '@/components/Header.vue'
import Carousel from '@/components/Carousel.vue'
import ItemsBanner from '@/components/ItemsBanner.vue'
import InstaGallery from '@/components/InstaGallery.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Header,
    Carousel,
    ItemsBanner,
    InstaGallery,
    PartnerLogo,
    Footer
  }
}
</script>
