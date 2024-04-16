<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
</script>

<template>
  <header>
    <Navbar />
  </header>
  <main>
    <Hero />
  </main>

  <RouterView />
</template>

