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
import Footer from './components/Footer.vue';
</script>

<template>
  <header>
    <Navbar />
  </header>
  <main>
    <Banner />
    <Hero />
    <Features />
    <Pricing />
    <Team />
    <Faqs />
    <Testimonials />
    <Newsletter />
    <Footer />
  </main>

  <RouterView />
</template>
