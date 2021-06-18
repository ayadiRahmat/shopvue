<template>
  <div class="name">
    <HeaderShop />
    <HeroShop />
    <WomanShop />
    <RelatedShop />
    <InstaShop />
    <PartnerShop />
    <FooterShop />
  </div>
  
</template>

<script>
// @ is an alias to /src
import HeaderShop from '@/components/HeaderShop.vue';
import HeroShop from '@/components/HeroShop.vue';
import WomanShop from '@/components/WomanShop.vue';
import InstaShop from '@/components/InstaShop.vue';
import PartnerShop from '@/components/PartnerShop.vue';
import RelatedShop from '@/components/RelatedShop.vue';
import FooterShop from '@/components/FooterShop.vue';

export default {
  name: 'home',
  components: {
    HeaderShop,
    HeroShop,
    WomanShop,
    InstaShop,
    PartnerShop,
    RelatedShop,
    FooterShop
    
  }
};
</script>
