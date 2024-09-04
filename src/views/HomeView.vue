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
  </div>
  <!--   
  <div class="cinema">
    <div class="juntosC">
      <h2 class="Lcinema">LIVROS</h2>
      <div class="bioC">
        <p class="clean">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Pariatur iste quis sint quos tenetur
          possimus
          quasi
          labore! Magni dolore nostrum quidem dolorem error iure, dolores temporibus explicabo necessitatibus ab
          minus.
          ima inventore animi totam aspernatur cupiditate. Laboriosam qui cupiditate nemo mollitia praesentium.
          Nesciunt, qui? Ex aspernatur doloribus aliquam obcaecati minus esse mollitia!
        </p>
        <div class="Lcontainer"></div>
      </div>
    </div>
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
  <div class="MaisE">Mais Emprestados</div>
  <div class="container3">
    <div class="LivrosME1">
      <div class="together2">
        <div class="L1"></div>
        <div class="clean2">
          <h2>Livros</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores corporis nostrum totam nihil suscipit
            repellendus animi consequuntur nemo ipsa, culpa exercitationem delectus! Corporis molestiae minus qui
            expedita! Ratione, doloremque itaque.</p>
        </div>
      </div>
    </div>
    <div class="LivrosME2">
      <div class="together2">
        <div class="L1"></div>
        <h2>Livros</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores corporis nostrum totam nihil suscipit
          repellendus animi consequuntur nemo ipsa, culpa exercitationem delectus! Corporis molestiae minus qui
          expedita! Ratione, doloremque itaque.</p>
      </div>
    </div>
    <div class="LivrosME3">
      <div class="together2">
        <div class="L1"></div>
        <h2>Livros</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores corporis nostrum totam nihil suscipit
          repellendus animi consequuntur nemo ipsa, culpa exercitationem delectus! Corporis molestiae minus qui
          expedita! Ratione, doloremque itaque.</p>
      </div>
    </div>
  </div> -->
  <FooterComponent />
</template>

<style scoped>
.container {
  width: 70%;
  margin: auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.carrossel {
  width: 90%;
  height: 20rem;
  display: flex;
  justify-content: space-between;
}

.textCarrossel {
  width: 45%;
  display: flex;
  flex-direction: column;
}

.imgCarrossel {
  width: 45%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #ddd;
}

.novidade {
  width: 40%;
  height: 20rem;
  margin: 2rem auto;
}

.headerNew {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.content {
  width: 100%;
  display: flex;
  justify-content: space-around;
}

.text {
  width: 45%;
  display: flex;
  flex-direction: column;
}

.img {
  width: 45%;
  background-color: #ddd;
}</style>