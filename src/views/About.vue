<template>
  <MainHeroReverse />
  <gridTwoByTwo />
  <threeColumn />
</template>

<script setup>
  import MainHeroReverse from '../components/layout/MainHeroReverse.vue';
  import gridTwoByTwo from '../components/layout/grid/gridTwoByTwo.vue';
  import threeColumn from '../components/layout/column/threeColumn.vue';

  components: {
    MainHeroReverse,
    gridTwoByTwo,
    threeColumn
  }

// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>
