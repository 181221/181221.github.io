<script setup lang="ts"></script>

<template>
  <div class="main-container">
    <h1 class="main-title">Peder <span class="main-title-span">&</span> Cecilie</h1>
    <h2 class="main-subtitle">12. July 2024 <span class="main-dot" /> Kjeller Gaard</h2>
    <h3 class="main-subtitle">Hold av datoen, mer informasjon kommer</h3>
  </div>
</template>

<style scoped>
.main-container {
  color: white;
}
.main-title {
  margin: 12px 0;
}
.main-dot {
  height: 12px;
  width: 12px;
  background-color: white;
  border-radius: 50%;
  display: inline-block;
  vertical-align: middle;
}
.main-title-span {
  display: block;
}

@media (min-width: 600px) {
  .main-title-span {
    display: inline;
  }
}
</style>
