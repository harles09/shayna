<template>
  <div class="home">
    <HeaderShayna/>
    <HeroSection/>
    <items-shayna/>
    <insta-shayna/>
    <partner-shayna/>
    <footer-shayna/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderShayna from '@/components/HeaderSyana.vue'
import HeroSection from '@/components/HeroSection.vue'
import ItemsShayna from '@/components/ItemsShayna.vue'
import InstaShayna from '../components/InstaShayna.vue'
import PartnerShayna from '../components/PartnerShayna.vue'
import FooterShayna from '../components/FooterShayna.vue'
export default {
  name: 'Home',
  components: {
    /* HelloWorld */
    HeaderShayna,
    HeroSection,
    ItemsShayna,
    InstaShayna,
    PartnerShayna,
    FooterShayna
  }
}
</script>

    