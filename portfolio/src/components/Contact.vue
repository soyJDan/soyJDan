<script setup lang="ts">

import Divisor from "@/components/Divisor.vue";
</script>

<template>
  <div class="container_contact">
    <h2>Connect with me</h2>

    <Divisor />
    <div class="contact">
      <a href="https://github.com/soyJDan" target="_blank"><img alt="Github" src="https://img.shields.io/badge/Github-%2312100E?style=for-the-badge&logo=Github&logoColor=white"></a>
      <a href="https://www.linkedin.com/in/soyJDan" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=LinkedIn&logoColor=white"></a>
      <a href="https://twitter.com/soyJDan" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/Twitter-%2312100E.svg?style=for-the-badge&logo=X&logoColor=white"></a>
    </div>
  </div>
</template>

<style scoped>
.container_contact {
  margin: 0 auto;
  text-align: center;
}

.container_contact h2 {
  color: white;
  font-weight: 600;
  margin-top: 3.5rem;
  margin-bottom: 0.15rem;
}

.container_contact .contact {
  margin-top: 1rem;

}
</style>