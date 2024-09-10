<script setup>
import HeaderComponent from '@/components/HeaderComponent.vue';
import FooterComponent from '@/components/FooterComponent.vue';
</script>

<template>
<HeaderComponent />
<link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=League+Spartan:wght@100..900&display=swap" rel="stylesheet">
    <div class="card">
    <div class="card-content">
      <div class="book-image">
      </div>
      <div class="book-info">
        <h3 class="book-title">Livro 1</h3>
        <p class="status">disponível</p>
        <p class="description">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aspernatur temporibus, qui nemo illum consequuntur placeat, blanditiis soluta perferendis repellendus, molestiae iste! Eligendi, fugiat esse maxime consectetur debitis accusamus atque cumque.
        </p>
        <div class="actions">
            
          <button class="button-icon">L</button>
          <button class="button-action">EMPRESTAR</button>
        </div>
      </div>
      <button class="close-button">X</button>
    </div>
  </div>
</template>
<style scoped>
.card {
  display: flex;
  align-items: center;
  justify-content: center;
  border: 6px solid #6bb47e;
  border-radius: 8px;
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

.book-image {
  margin-right: 20px;
  background-color: #666;
  border-radius: 4px;
  width: 50%;
  height: 280px;
}
.book-info {
  flex: 1;
}

.book-title {
  font-size: 24px;
  margin: 0;
  color: #36834a;
}

.status {
  color: #6bb47e;
  font-weight: bold;
  margin: 8px 0;
}

.description {
  font-size: 12px;
  color: #666;
  line-height: 1.4;
}

.actions {
  margin-top: 16px;
  display: flex;
  align-items: center;
}

.button-icon {
  background-color: #6bb47e;
  border: none;
  color: white;
  padding: 8px;
  margin-right: 16px;
  border-radius: 4px;
}

.button-action {
  background-color: #f48942;
  border: none;
  color: white;
  padding: 8px 16px;
  border-radius: 4px;
  cursor: pointer;

}

.button-action:hover {
  background-color: #d97d38;
}

.close-button {
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