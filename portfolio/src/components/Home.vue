<script setup lang="ts">

  const urlImage = "https://i.imgur.com/gOmSTjv.png";
  const altImage = "Kermit The Frog";

</script>

<template>
  <div id="home">
    <img src="https://i.imgur.com/gOmSTjv.png" alt={{altImage}} />

    <div class="title">
      <h1>Da</h1>
      <h2>SF</h2>
    </div>
  </div>
</template>

<style scoped>
  .title {
    position: absolute;
    top: 5rem;
    left: 2rem;
    width: 17rem;
  }
</style>