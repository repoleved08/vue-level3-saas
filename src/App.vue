<script setup>
import { RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Features from './components/Features.vue';
import Pricing from './components/Pricing.vue';
import Team from './components/Team.vue';
import Faqs from './components/Faqs.vue';
import Testimonials from './components/Testimonials.vue';
import Newsletter from './components/Newsletter.vue';
import Banner from './components/Banner.vue';
</script>

<template>
  <header>
    <Banner />
    <Navbar />
   
  </header>
  <main>
    <Hero />
    <Features />
    <Pricing />
    <Team />
    <Faqs />
    <Testimonials />
    <Newsletter />
  </main>

  <RouterView />
</template>
