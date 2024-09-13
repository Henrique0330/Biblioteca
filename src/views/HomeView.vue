<script setup>
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>

<template>
  <HeaderComponent />
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
        <h2>1 BEST SELLER</h2>
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
    <h1 class="tittle">MAIS EMPRESTADOS</h1>
    <div class="container2">
    <div class="MaisEmprestados">
      <div class="MaisEL"></div>
      <h3 class="livros">Livro 1</h3>
      <p class="PMaisE">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum quos commodi repellat non repudiandae nostrum eos culpa nobis deserunt assumenda exercitationem, mollitia numquam tempora ullam nesciunt eum quo nulla cum!</p>
    </div>
    <div class="MaisEmprestados2">
      <div class="MaisEL"></div>
      <h3 class="livros2">Livro 2</h3>
      <p class="PMaisE2">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti vitae fugiat omnis dolor a similique obcaecati enim officiis aut ipsam quisquam, adipisci ut, quod perferendis? Corrupti, necessitatibus. Consectetur, sunt sapiente.</p>
    </div>
    <div class="MaisEmprestados3">
      <div class="MaisEL"></div>
      <h3 class="livros">Livro 3</h3>
      <p class="PMaisE">Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit ut, natus, a soluta sequi dolor eum repudiandae praesentium non doloremque ipsam laudantium dolorem iste maxime voluptas culpa recusandae corporis quasi.</p>
    </div>
  </div>
  </div>
  <FooterComponent />
</template>
<style scoped>
.carousel-inner img {
    width: 100%;
    height: 100%;
  }
  .livros2{
    color: #8FD085;
    margin: 30px;
  }
  .PMaisE2{
    color: #8FD085;
    margin: 30px 1.4rem 0 30px;
  }
.PMaisE{
  margin: 30px 1.4rem 0 30px;
  color: #ffff;
}
.livros{
  margin: 30px;
  color: #ffffff;
}

.tittle{
  padding-top: 50px;    
  color: #D08597;
}
.container2{
  display: flex;
  gap: 4.4rem;
}
.MaisEL{
  width: 280px;
  height: 370px;
  background-color: #D9D9D9;
  margin: 30px 0 0 30px;
  border-radius: 10px ;
}

.MaisEmprestados{
  background-color: #D08597;
  width: 340px;
  height: 675px;
  border-radius: 10px;
  margin-top: 40px;
}

.MaisEmprestados2{
  border: #8FD085 solid;
  width: 340px;
  height: 675px;
  border-radius: 10px;
  margin-top: 40px;
}

.MaisEmprestados3{
  background-color: #85B5D0;
  width: 340px;
  height: 675px;
  border-radius: 10px;
  margin-top: 40px;
}

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
  margin: 3rem 0 0 0;
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