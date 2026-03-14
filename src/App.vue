<template>
  <div class="font-sans text-gray-800 bg-gray-50">
    <Header />
    <Hero />
    <Projects />
    <Contact />
    <footer class="bg-white text-center py-6 mt-12 shadow-inner">
      &copy; 2026 Julius Alivio. All rights reserved.
    </footer>
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'
</script>