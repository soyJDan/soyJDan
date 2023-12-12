<script setup lang="ts">

import Home from "@/components/Home.vue";
import Skills from "@/components/Skills.vue";
import Contact from "@/components/Contact.vue";

const siteProps = {
  name: 'Daniel Romero',
  title: 'Software Developer',
  email: 'juandanielromerobedoya@gmail.com',
  github: 'soyJDan',
  twitter: 'soyJDan',
  linkedin: 'soyJDan'
}
</script>

<template>
  <main>
    <Home />
    <Contact />
    <Skills />
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
