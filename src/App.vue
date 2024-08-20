<script setup>
</script>

<template>
  <div class="novidade">
    <h2 class="tittle">Novidade</h2>
    <div class="container">
    <div class="livroN"></div>
    <div class="livro1">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto repellendus, ducimus aliquam perferendis quidem iure natus corporis, voluptatibus vero amet doloremque est, unde reprehenderit distinctio. Rerum maxime debitis aut minus?</div></div>
  </div>
</template>

<style scoped>
  .novidade{
    background-color: #85B5D0;
    width: 450px;
    height: 350px;
    border-radius: 1rem;
    padding-left: 38px;
  }

  .livroN{
    background-color: #D9D9D9;
    width: 180px;
    height: 250px;
    border-radius: 1rem;
  }

  .tittle{
    text-align: center;
    font-size: 25px;
    margin:.5rem 0 1rem 0;
  }
.container{
  display: flex;
  width: 100%;
  gap: 1rem;
}
  .livro1{
    width: 180px;
    height: 250px;
  }

</style>
130