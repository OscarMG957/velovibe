<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheNavbar from './components/TheNavbar.vue';
import TheHeader from './components/TheHeader.vue';
</script>

<template>
  <TheNavbar />

  <TheHeader />

  <div class="container">
    <RouterView />
  </div>
  
</template>
