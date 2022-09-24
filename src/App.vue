<template>
  <div class="container text-center">
    <div class="flex justify-center">
      <img alt="Vue logo" src="./assets/logo.png" />
    </div>
  </div>
  <div class="container mx-auto">
    <div>
      <Nav />
    </div>
    <router-view></router-view>
  </div>
</template>

<script setup>
import Nav from './components/layout/Nav.vue'

// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>
