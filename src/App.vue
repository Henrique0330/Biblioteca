<script setup>
</script>

<template>
  <header>

  </header>
  <div class="cinema">
    <h2>LIVROS</h2>
  </div>
  <div class="together">
    <div class="novidade">
      <h2 class="tittle">Novidade</h2>
      <div class="container">
        <div class="livroN"></div>
        <div class="livro1">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto repellendus, ducimus
          aliquam perferendis quidem iure natus corporis, voluptatibus vero amet doloremque est, unde reprehenderit
          distinctio. Rerum maxime debitis aut minus?</div>
      </div>
    </div>
    <div class="melhoresL">
      <h1 class="tittleN">1 Best seller</h1> 
      <div class="obs">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Architecto repellendus, ducimus
          aliquam perferendis quidem iure natus corporis, voluptatibus vero amet doloremque est, unde reprehenderit
          distinctio. Rerum maxime debitis aut minus?</div>
          <div class="imagen"></div>
    </div>
  </div>
</template>

<style scoped>
.novidade {
  background-color: #85B5D0;
  width: 450px;
  height: 350px;
  border-radius: 1rem;
  padding-left: 38px;
}

.livroN {
  background-color: #D9D9D9;
  width: 180px;
  height: 250px;
  border-radius: 1rem;
}

.tittle {
  text-align: center;
  font-size: 25px;
  margin: .5rem 0 1rem 0;
}

.tittleN {
  text-align: center;
  margin: 40px 0 16px 0;
  font-size: 70px;
}

.container {
  display: flex;
  width: 100%;
  gap: 1rem;
}

.livro1 {
  width: 180px;
  height: 250px;
}

.obs{
  width: 180px;
  height: 250px;
}

.imagen{
  background-color: #ff0000;
  width: 10px;
  height: 10px;
  border-radius: 1rem;
}

.melhoresL {
  width: 571px;
  height: 350px;
  border: #F0C65B solid;
  border-radius: 1rem;
  color: #FFE999;
  font-size: 455px 130px;
  margin-left: 45px;
}

header {
  width: 100%;
  height: 120px;
  margin: 0 0 3rem 0;
  background-color: #8FD085;
}

.together {
  display: flex;
  margin-left: 318px;
  margin-top: 45px;
}

.cinema {
  width: 1060px;
  height: 300px;
  background-color: #D08597;
  border-radius: 0.5rem;
  margin-left: 350px;
  margin-top: 40px;
}
</style>