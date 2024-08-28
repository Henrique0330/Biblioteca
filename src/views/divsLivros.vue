<script setup>

</script>

<template>
        
        <div class="livros1">
            <div class="livro1">
                <div class="imagem"></div>
            </div>
            <div class="livro1">
                <div class="imagem"></div>
            </div>
            <div class="livro1">
                <div class="imagem"></div>
            </div>
        </div>
        <div class="livros1">
            <div class="livro2">
                <div class="imagem"></div>
            </div>
            <div class="livro2">
                <div class="imagem"></div>
            </div>
            <div class="livro2">
                <div class="imagem"></div>
            </div>
        </div>
</template>

<style scoped>
.livros{
}
.livros1 {
    display: flex;
    justify-content: space-evenly;
    margin-bottom: 20px;    
}

.imagem{
    width: 200px;
    height: 380px;
    background-color: #D9D9D9;
}

.livro1 {
    width: 280px;
    height: 380px;
    border: #FF517B 5px solid;
    border-radius: 16px;
}

.livro2 {
    width: 280px;
    height: 380px;
    border: #FF517B 5px solid;
    border-radius: 16px;
}


</style>