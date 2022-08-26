<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeaderMcact />
    <HeroMcact />
    <ProductMcact />
    <InstaMcact />
    <PartnerMcact />
    <FooterMcact />

  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue';
import HeaderMcact from '@/components/HeaderMcact.vue';
import HeroMcact from '@/components/HeroMcact.vue';
import ProductMcact from '@/components/ProductMcact.vue';
import InstaMcact from '@/components/InstaMcact.vue';
import PartnerMcact from '@/components/PartnerMcact.vue';
import FooterMcact from '@/components/FooterMcact.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderMcact,
    HeroMcact,
    ProductMcact,
    InstaMcact,
    PartnerMcact,
    FooterMcact,
  }
}
</script>
