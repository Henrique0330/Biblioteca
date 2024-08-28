<template>
    <header>
        <div>
            <h1>Biblioteca</h1>
        </div>
        <div class="barra">
            <img src="../assets/logo.svg" alt="Ícone de pesquisa" class="icon">
            <input type="pesquisa" name="pesquisa" placeholder="Buscar">
        </div>
    </header>
</template>

<style scoped>

header {
    display: flex;
    justify-content: space-evenly;
    width: 100%;
    height: 120px;
    margin: 0 0 3rem 0;
    background-color: #8FD085;
}
header div h1{
    margin-top: 3rem;
}

.barra {
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
}

.barra img.icon {
    width: 20px;
    height: auto;
    position: absolute;
    left: 10px;

}

.barra input {
    padding-left: 40px;
    width: 100%;
    max-width: 300px;
    height: 36px;
    border-radius: 10px;
    border: 1px solid #FFFFFF;
    background-color: #8FD085;
    color: white;
    font-size: 16px;
}

.barra input::placeholder {
    color: white;
    font-size: 15px;
}


@media (max-width: 768px) {
    .barra input {
        max-width: 250px;
        padding-left: 35px;
    }
}

@media (max-width: 480px) {
    .barra input {
        max-width: 200px;
        padding-left: 30px;
    }
}
</style>