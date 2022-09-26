<template>
  <Header />
  <div class="container mx-auto">
    <router-view></router-view>
  </div>
  <Footer />
</template>

<script setup>
  import Header from './components/layout/Header.vue'
  import Footer from './components/layout/Footer.vue';

  components: {
    Header,
    Footer
  }

// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>
