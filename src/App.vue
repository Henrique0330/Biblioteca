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
      <div class="container2">
        <div class="bio">Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore maiores debitis amet ipsa
          accusamus earum, fugit perferendis velit id soluta temporibus illo! Ullam, error!</div>
        <div class="imagem"></div>
      </div>
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

.container2{
  display: flex;
  gap: 2rem;
  padding-top: 30px;
}

.imagem {
  background-color: #D9D9D9;
  width: 270px;
  height: 130px;
  border-radius: 10px;
}

.bio {
  width: 180px;
  height: 250px;
  padding-left: 50px;
}

.tittle {
  text-align: center;
  font-size: 25px;
  margin: .5rem 0 1rem 0;
}

.tittleN {
  text-align: center;
  font-size: 90px;
  margin: .5rem 1rem 1rem 0;
  margin-top: 20px;
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