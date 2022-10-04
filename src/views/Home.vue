<template>
  <div>
    <img class="h-full w-full object-cover" src="../assets/promo_main_1.jpg" alt="" />
  </div>
  <MainHero ctaText="This is the CTA title" />
</template>

<script setup>
  import MainHero from '../components/layout/MainHero.vue';

  components: {
    MainHero
  }

</script>
