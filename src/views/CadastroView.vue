<script setup>
</script>
<template>
    <div class="container">
        <form action="" class="cadastro">
            <h1>CADASTRO</h1>
            <h3>Você é:</h3>
            <div class="EstudanteResponsavel">
            <button class="responsavel">Responsavel</button>
            <button class="estudante">Estudante</button>
        </div>
            <label for="Nome">Nome</label>
            <input type="text" placeholder="Nome">
            <label for="Email">Email</label>
            <input type="email" name="" id="" placeholder="Email">
            <label for="Senha">Senha</label>
            <input type="password" name="" id="" placeholder="Senha">
            <label for="Confirme senha">Confirme a senha</label>
            <input type="password" name="" id="" placeholder="Confirme sua senha">
            <label for="CPF"></label>
            <input type="text" name="" id="" placeholder="CPF">
            <label for="CPF do responsável">CPF do responsável</label>
            <input type="text" name="" id="" placeholder="CPF do responsável">
            <button class="BotaoCadastro">Cadastrar</button>
            <a href="">Já tenho conta!</a>
        </form>
    </div>
</template>
<style scoped>
.container{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
h1{
    text-align: center;
    margin: 92px;
    color: #656565;
    font-family: "League Spartan", sans-serif;

}
form.cadastro{
    display: flex;
    flex-direction: column;
}
input {
    width: 450px;
    height: 46px;
    border-radius: 10px;
    border-color: black;
    opacity: 0.5;
    border-width: 1px;
    padding: 0 10px; 
}
.BotaoCadastro{
    border-radius: 10px;
    background-color: #8FD085; 
    width: 247px;
    height: 46px;
    border: none;
    margin: 51px auto;
    font-family: "League Spartan", sans-serif;
}
.BotaoCadastro:hover{
    background-color: #2b6a22;
}
label{
    margin: 14px 0;
    font-family: "League Spartan", sans-serif;
}
a{
    text-align: center;
    color: #656565;
}
.responsavel{
    background-color: #D9D9D9;
    width: 145px;
    height: 46px;
}
.estudante{
    background-color: #8FD085;
    width: 145px;
    height: 46px;
}


</style>