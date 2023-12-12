<script setup lang="ts">
  const description = "I am a programmer and software developer who is passionate about continuous learning.";

  const skillsList = [
    "TypeScript",
    "Java",
    "Dart",
    "Git",
    "Docker",
    "PostgreSQL",
    "Oracle",
    "And a few more...",
  ];
</script>

<template>
  <h2>About Myself</h2>
  <p class="large">{{ description }}</p>
  <hr>
  <ul class="skills">
    <li v-for="skill in skillsList" :key="skill">{{ skill }}</li>
  </ul>
</template>

<style scoped>
  .large {
    backgroundColor: white;
    width: 50%;
    padding: 4rem;
    margin: 3rem auto;
    textAlign: center;
    font-size: 24px;
  }

  .skills {
    text-align: left;
    columns: 2;
    font-size: 1.25rem;
    margin: 2rem 3rem;
    gap: 3rem;
  }
</style>