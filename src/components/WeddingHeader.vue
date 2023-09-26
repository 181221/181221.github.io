<script setup lang="ts"></script>

<template>
  <div class="main-container">
    <h1 class="main-title">Peder <span class="main-title-span">&</span> Cecilie</h1>
    <h2 class="main-subtitle">
      <span class="main-subtitle-date">13. July 2024 </span><span class="main-dot" /> <span>Kjeller Gaard</span>
    </h2>
  </div>
</template>

<style scoped>
.main-container {
  font-family: Playfair Display;
  color: white;
  max-width: 1280px;
  margin: 0 auto;
  margin-top: 12px;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.main-title {
  margin: 0 0;
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

.main-subtitle-date {
  display: block;
  margin-bottom: 0.1em;
}
.main-dot {
  display: none;
}
@media (min-width: 600px) {
  .main-title-span {
    display: inline;
  }

  .main-subtitle-date {
    display: inline;
  }
  .main-dot {
    display: inline-block;
  }
}
</style>
