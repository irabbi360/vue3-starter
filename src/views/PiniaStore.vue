<script setup>
import { useCounterStore } from '@/stores/counter'
const store = useCounterStore()
</script>

<template>
  <div class="greetings">
    <h3>Pinia The intuitive store for Vue.js</h3>
    <h1 class="green">{{ store.count }}</h1>
    <div>
      <button @click="store.increment">1+</button>
    </div>
  </div>
</template>

<style scoped>

</style>
