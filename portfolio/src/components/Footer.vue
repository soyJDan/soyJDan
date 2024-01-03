<template>
  <div class="container-footer">
    <i class="imageHeader"></i>
    <p>With ❤️ soyJDan</p>
  </div>
</template>

<style scoped>
  .container-footer {
    position: fixed;
    bottom: 0;
    left: 0;
    width: 100%;
  }

  .container-footer p {
    text-align: center;
    color: white;
    padding: 1rem;
  }

  .container-footer i {
    position: absolute;
    background-image: url("./../../public/mega-creator.png");
    background-repeat: no-repeat;
    background-position: left bottom;
    height: 10rem;
    width: 10rem;
    background-size: 5rem;
    bottom: 0;
    margin-left: 40%;
  }

</style>