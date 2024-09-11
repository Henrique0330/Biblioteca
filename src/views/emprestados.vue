<script setup>
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>
<template>
    <HeaderComponent />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&display=swap" rel="stylesheet">
    <div class="container">
    <h1 class="titulo">EMPRESTADOS</h1>
    <div class="livros-emprestados">
        <div class="livro">
            <div class="imagem"></div>
            <div class="content-livro">
                <div class="texto-content">
                    <h2>Livro</h2>
                    <h5>devoluções</h5>
                </div>
            </div>
        </div>
        <div class="livro">
            <div class="imagem"></div>
            <div class="content-livro">
                <div class="texto-content">
                    <h2>Livro</h2>
                    <h5>devoluções</h5>
                </div>
            </div>
        </div>
        <div class="livro">
            <div class="imagem"></div>
            <div class="content-livro">
                <div class="texto-content">
                    <h2>Livro</h2>
                    <h5>devoluções</h5>
                </div>

            </div>
        </div>
    </div>
    <button class="multa">MULTA R$ 0,00</button>
</div>

</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&display=swap');

.container{
    height: 80vh;
    padding: 3rem 0;
    width: 100%;
    background-color: #689062;
}
*{
    font-family:"League Spartan", sans-serif;
    color: #FFFFFF;
}
.titulo{
    text-align: center;
    letter-spacing: 6px;
    margin-top: 69px;
}
.livros-emprestados{
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-top: 64px;
}
.imagem{
    width: 100%;
    height: 350px;
}
.livro{
    padding: 1rem;
    border: white  solid;
    border-radius: 20px;
    width: 273px;
    height: 453px;
}
.texto-content{
    margin: 30px;
}
h2{
    text-align: center;
    font-size: 30px;
    letter-spacing: 3px;
}
h5{
    text-align: center;
    margin: 5px auto;
    font-size: 25px;
    letter-spacing: 5px;
}
</style>