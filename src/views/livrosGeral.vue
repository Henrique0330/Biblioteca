<script setup>
import { ref } from "vue"

const props = defineProps({
  isOpen: Boolean,
  route: String
})

const emit = defineEmits(["update:isOpen"])

const closeModal = () => {
  emit("update:isOpen", false)
}

</script>

<template>
  <main v-if="isOpen">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&display=swap" rel="stylesheet">
    <div class="card">
      <div class="card-content">
        <div class="livro-imagem">
        </div>
        <div class="livro-info">
          <h3 class="livro-titulos">Livro 1</h3>
          <p class="status">disponível</p>
          <p class="descriçao">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur temporibus, qui nemo illum consequuntur
            placeat, blanditiis soluta perferendis repellendus, molestiae iste! Eligendi, fugiat esse maxime consectetur
            debitis accusamus atque cumque.
          </p>
          <div class="botoes">
            <button class="botao-livre">L</button>
            <button class="botao-emprestar"  @click="this.$router.push(`${route}`)">EMPRESTAR</button>
          </div>
        </div>
        <button class="fechar-button" @click="closeModal">X</button>
      </div>
    </div>
  </main>
</template>
<style scoped>
main {
  width: 100%;
  position: fixed;
  left: 0;
  top: 0;
  background-color: rgba(0, 0, 0, 0.562);
  backdrop-filter: 10px;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  z-index: 15;
}

.card {
  display: flex;
  align-items: center;
  justify-content: center;
  border: 8px solid #6bb47e;
  border-radius: 10px;
  padding: 16px;
  background-color: #f9f8f6;
  position: relative;
  max-width: 1000px;
  height: 500px;
  margin: auto;
}

.card-content {
  display: flex;
  width: 100%;
}

.livro-imagem {
  margin-right: 40px;
  background-color: #666;
  border-radius: 4px;
  width: 283px;
  height: 383.18px;
  border-radius: 10px;
  margin-left: 90px;
}

.livro-info {
  flex: 1;
  display: grid;
  align-content: space-around;

}

.livro-titulos {
  font-size: 40px;
  margin: 0;
  color: #36834a;
  text-align: center;
  letter-spacing: 8px;
}

.status {
  color: #6bb47e;
  font-weight: bold;
  margin: 8px 0;
  text-align: center;
  font-size: 25px;
  letter-spacing: 8px;
}

.descriçao {
  font-size: 25px;
  color: #666;
  line-height: 1.4;
  text-align: justify;
}

.botoes {
  margin-top: 16px;
  display: flex;
  align-items: center;
}

.botao-emprestar {
  background-color: #f48942;
  border: none;
  color: white;
  margin: auto;
  border-radius: 23px;
  cursor: pointer;
  width: 393px;
  height: 60px;
  font-size: 23px;
  letter-spacing: 10px;
}

.botao-livre {
  background-color: #6bb47e;
  border: none;
  color: white;
  padding: 8px 16px;
  border-radius: 4px;
  cursor: pointer;
  width: 50px;
  height: 50px;
  font-size: 20px;
}

.button-livre:hover {
  background-color: #d97d38;
}

.fechar-button {
  background: none;
  border: none;
  color: #666;
  font-size: 16px;
  position: absolute;
  right: 16px;
  top: 16px;
  cursor: pointer;
}
</style>