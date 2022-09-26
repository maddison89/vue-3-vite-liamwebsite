<template>
  <router-link v-for="link in navigation" :key="link.name" :to="link.href" class="text-base font-medium text-white hover:text-indigo-50">{{ link.name }}</router-link>
</template>
<script setup>
  const navigation = [
    { name: 'Home', href: '/' },
    { name: 'About', href: '/about' },
  ]
  </script>