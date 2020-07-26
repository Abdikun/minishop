<template>
  <div class="home">
    <HeaderMinishop />
    <CarouselMinishop />
    <BannerMinishop />
    <InstaMinishop />
    <PartnerMinishop />
    <FooterMinishop />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderMinishop from '@/components/HeaderMinishop.vue'
import CarouselMinishop from '@/components/CarouselMinishop.vue'
import BannerMinishop from '@/components/BannerMinishop.vue'
import InstaMinishop from '@/components/InstaMinishop.vue'
import PartnerMinishop from '@/components/PartnerMinishop.vue'
import FooterMinishop from '@/components/FooterMinishop.vue'

export default {
  name: 'Home',
  components: {
    HeaderMinishop,
    CarouselMinishop,
    BannerMinishop,
    InstaMinishop,
    PartnerMinishop,
    FooterMinishop
  }
}
</script>
