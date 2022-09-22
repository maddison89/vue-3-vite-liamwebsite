<template>
  <h1>{{ msg }}</h1>

  <p>
    This is a test
  </p>

  <h1 class="text-3xl font-bold underline">
    Hello world!
  </h1>

  <button type="button" @click="count++">count is: {{ count }}</button>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>

<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
