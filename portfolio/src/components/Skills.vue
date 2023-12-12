<script setup lang="ts">

import Divisor from "@/components/Divisor.vue";
</script>

<template>
  <div class="container_skills">
    <h2>Skills</h2>

    <Divisor />
    <div class="container_tools">
      <img alt="Java" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/java.svg" width="40"/>
      <img alt="Spring" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/spring.svg" width="40"/>
      <img alt="TypeScript" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/typescript-icon.svg" width="40"/>
      <img alt="PostgreSQL" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/postgresql.svg" width="40"/>
      <img alt="Git" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/git-icon.svg" width="40"/>
      <img alt="React" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/react.svg" width="40"/>
      <img alt="Docker" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/docker-icon.svg" width="40"/>
      <img alt="Dart" src="https://raw.githubusercontent.com/get-icon/geticon/fc0f660daee147afb4a56c64e12bde6486b73e39/icons/dart.svg" width="40">  And a few more...
    </div>
  </div>

</template>

<style scoped>
  .container_skills {
    margin: 0 auto;
    text-align: center;
  }

  .container_skills h2 {
    color: white;
    font-weight: 600;
    margin-top: 3.5rem;
    margin-bottom: 0.15rem;
  }

  .container_skills .container_tools {
    margin-top: 1rem;

  }
</style>