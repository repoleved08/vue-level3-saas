<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Features from './components/Features.vue';
import Pricing from './components/Pricing.vue';
import Team from './components/Team.vue';
import Faqs from './components/Faqs.vue';
import Testimonials from './components/Testimonials.vue';
</script>

<template>
  <header>
    <Navbar />
  </header>
  <main>
    <Hero />
    <Features />
    <Pricing />
    <Team />
    <Faqs />
    <Testimonials />
  </main>

  <RouterView />
</template>
