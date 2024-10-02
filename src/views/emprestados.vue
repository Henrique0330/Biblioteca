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
                    <h2>LIVRO</h2>
                    <h5>Devolução:</h5>
                </div>
            </div>
        </div>
        <div class="livro">
            <div class="imagem"></div>
            <div class="content-livro">
                <div class="texto-content">
                    <h2>LIVRO</h2>
                    <h5>Devolução:</h5>
                </div>
            </div>
        </div>
        <div class="livro">
            <div class="imagem"></div>
            <div class="content-livro">
                <div class="texto-content">
                    <h2>LIVRO</h2>
                    <h5>Devolução:</h5>
                </div>

            </div>
        </div>
    </div>
    <div class="botoes">
    <button class="multa">MULTA <br>R$ 0,00</button>
    <button class="voltar">VOLTAR</button>
    </div>
</div>

</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&display=swap');

.container{
    height: 90vh;
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
.botoes{
    display: flex;
    justify-content: center;
    margin: 73px auto;
    flex-direction: column;
    align-items: center;
    background-color: #689062;

}
.multa{
    color: #689062;
    background-color: white;
    width: 200px;
    border-radius: 20px;
    height: 90px;
    border: none;
    cursor: pointer;
    font-size: 22px;
    font-weight: bold;
    letter-spacing: 5px;
}
.voltar{
    margin-top: 8px;
    background-color: #689062;
    height: 70px;
    border: none;
    cursor: pointer;
    font-size: 25px;
    font-weight: bold;
    letter-spacing: 2px;
}

</style>