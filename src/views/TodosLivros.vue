<script setup>
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>

<template>
    <HeaderComponent />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&display=swap" rel="stylesheet">
    <h1 class="titulo">TODOS</h1>
    <div class="livros1">
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 1</h2>
                    <p class="disp">disponível</p>
                </div>

            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 6</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 2</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 3</h2>
                    <p class="disp">disponível</p>
                </div>
            </div>
        </div>
    </div>
    <div class="livros1">
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 6</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 4</h2>
                    <p class="indisp">indisponível</p>
                </div>

            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 5</h2>
                    <p class="disp">disponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 6</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
    </div>
    <div class="livros1">
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 6</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 4</h2>
                    <p class="indisp">indisponível</p>
                </div>

            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 5</h2>
                    <p class="disp">disponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 6</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
    </div>
    <div class="livros1">
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 6</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 4</h2>
                    <p class="indisp">indisponível</p>
                </div>

            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 5</h2>
                    <p class="disp">disponível</p>
                </div>
            </div>
        </div>
        <div class="livro1">
            <div class="imagem"></div>
            <div class="contentLivro">
                <div class="textContent">
                    <h2>LIVRO 6</h2>
                    <p class="indisp">indisponível</p>
                </div>
            </div>
        </div>
    </div>
    <h2 class="titulo verMais">VER MAIS ></h2>
    <FooterComponent />
</template>

<style scoped>
h2 {
    color: #689062;
}
.verMais{
    padding-top: 3rem;
}
.titulo {
    text-align: center;
    color: #689062;
    margin: 0 0 3rem 0;
}
.livros1 {
    display: flex;
    justify-content: center;
    margin-bottom: 20px;
    gap: 5rem;
    align-items: center;

}

.imagem {
    width: 206px;
    height: 185px;
    background-color: #D9D9D9;
    border-radius: .5rem;
}

.livro1 {
    padding: .5rem;
    display: flex;
    flex-direction: column;
    width: 100%px;
    height: 252px;
    border: #689062 6px solid;
    border-radius: 16px;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.contentLivro {
    width: 100%;
    height: 70px;
    display: flex;
    justify-content: space-around;
}

.textContent {
    display: flex;
    flex-direction: column;
    width: 70%;
}

h2 {
    margin: .5rem 0 0 0;
}

p {
    margin: 0;
}

.classificacao {
    width: 20%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 20px;
    margin-left: 37px;

}

.classificacao>img {
    width: 50px;
    height: 50px;
    border-radius: 4px;
}

.disp {
    color: #4FBD3D;
    font-size: 25px;
}

.indisp {
    color: #FF517B;
    font-size: 25px;
}
</style>