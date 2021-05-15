<template>
  <div class="principalPage">
    <Navbar />
    <Carousel />
    <Design />
    <Cards />
    <Carousel2 />
    <AboutAlhambra />
    <WovenTales />
    <Hashtag />
    <Footer />
    
  </div>
</template>

<script>
import Carousel from '@/components/Carousel.vue';
import Navbar from '@/components/Navbar.vue';
import Design from '@/components/Design.vue';
import Cards from '@/components/Cards.vue';
import Carousel2 from '@/components/Carousel2.vue';
import AboutAlhambra from '@/components/AboutAlhambra.vue';
import WovenTales from '@/components/WovenTales.vue';
import Hashtag from '@/components/Hashtag.vue';
import Footer from '@/components/Footer.vue';

export default {
  name: "Page",
  components: {
    Carousel,
    Navbar,
    Design,
    Cards,
    Carousel2,
    AboutAlhambra,
    WovenTales,
    Hashtag,
    Footer
  },
};
</script>


<style lang="scss" scoped>
.principalPage {
  font-family: "Space Grotesk", Helvetica, Arial, sans-serif;
  color: black;  
}
</style>
