<script setup lang="ts">
import Header from './components/Header.vue'
import About from '@/components/About.vue'
import Home from '@/components/Home.vue'

const siteProps = {
  name: "Daniel Romero",
  title: "Software Developer",
  email: "juandanielromerobedoya@gmail.com",
  github: "soyJDan",
  twitter: "soyJDan",
  linkedin: "soyJDan",
}
</script>

<template>
  <header>
    <Header />
  </header>

  <main>
    <Home />
    <About />

  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }
}
</style>
