<script setup>
</script>

<template>
  <div class="container">
    <div class="carrossel">
      <div class="textCarrossel">
        <h2>LIVROS</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatibus ipsa modi eaque minus vel atque quia
          unde labore incidunt pariatur ratione, sint in magni consequatur, dolorum asperiores nam autem commodi?Lorem
          ipsum dolor sit amet, consectetur adipisicing elit. Reiciendis, error rem qui vel saepe accusamus tempore ipsa
          ipsum, porro doloremque quam quo molestias praesentium eaque hic temporibus minima expedita magnam?
        </p>
      </div>
      <div></div>
      <div class="imgCarrossel"></div>
    </div>
    <div class="novidade">
      <div class="headerNew">
        <h2>NOVIDADE</h2>
      </div>
      <div class="content">
        <div class="text">
          <h2>LIVRO 0</h2>  
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, ducimus accusamus sequi nisi voluptas
            assumenda. Suscipit eius temporibus optio ratione aut porro quisquam atque, ducimus magnam quibusdam at, ullam
            libero.</p>
        </div>
        <div class="img"></div>
      </div>
    </div>
    <div class="melhorL">
      <div class="headerNew">
        <h2>1 BEST SALLER</h2>
      </div>
      <div class="content">
        <div class="text">
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, ducimus accusamus sequi nisi voluptas
            assumenda. Suscipit eius temporibus optio ratione aut porro quisquam atque, ducimus magnam quibusdam at, ullam
            libero.</p>
        </div>
        <div class="img"></div>
      </div>
    </div>
  </div>
  <FooterComponent />
</template>

<style scoped>
.container {
  width: 70%;
  margin: auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  font-size: 18px;
}

.carrossel {
  width: 90%;
  height: 20rem;
  display: flex;
  justify-content: space-between;
  background-color: #D08597;
  border-radius: 10px;
}

.textCarrossel {
  width: 45%;
  display: flex;
  flex-direction: column;
  padding-top: 60px;
  padding-left: 50px;
  color: #ddd;
}

.imgCarrossel {
  width: 45%;
  height: 70%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #ddd;
  border-radius: 10px;
  margin-right: 50px;
  margin-top: 50px;
}

.novidade {
  width: 40%;
  height: 20rem;
  margin: 2rem auto;
  background-color: #85B5D0;
  border-radius: 10px;
  color:#ddd;
  border-radius: 10px;
  
}

.melhorL{
  width: 40%;
  height: 20rem;
  margin: 2rem auto;
  border: #F0C65B solid;
  color: #F0C65B;
  border-radius: 10px;
}

.headerNew {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 30px;
}

.content {
  width: 100%;
  display: flex;
  justify-content: space-around;
  margin-top: 40px;
}

.text {
  width: 45%;
  display: flex;
  flex-direction: column;
}

.img {
  width: 150px;
  height: 200px;
  background-color: #ddd;
  border-radius: 10px;
}</style>