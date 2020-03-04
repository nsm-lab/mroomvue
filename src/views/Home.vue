<template>
  <div class="home">

    <HeaderMroom />
    <HeroMroom />
    <SliderMroom />
    <InstaMroom />
    <PartnerMroom />
    <FooterMroom />

  </div>
</template>

<script>
// // @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderMroom from "@/components/HeaderMroom.vue";
import HeroMroom from "@/components/HeroMroom.vue";
import SliderMroom from "@/components/SliderMroom.vue";
import InstaMroom from "@/components/InstaMroom.vue";
import PartnerMroom from "@/components/PartnerMroom.vue";
import FooterMroom from "@/components/FooterMroom.vue";


export default {
  name: 'Home',
  components: {
    HeaderMroom,
    HeroMroom,
    SliderMroom,
    InstaMroom,
    PartnerMroom,
    FooterMroom
  }
}
</script>