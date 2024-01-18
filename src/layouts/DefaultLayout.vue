<script setup>
import { RouterLink, RouterView } from 'vue-router'

import Navbar from '../components/navbar/Navbar.vue';
import Sidebar from '../components/sidebar/Sidebar.vue';
</script>

<template>
  <Sidebar />
  <div class="app-content">
    <Navbar />
    <main>
      <RouterView />
    </main>
  </div>
</template>

<style scoped>

</style>
