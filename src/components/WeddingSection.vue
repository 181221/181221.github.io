<template>
  <div class="info-section">
    <WeddingTitle><slot name="title"></slot></WeddingTitle>
    <p class="info-text"><slot name="content"></slot></p>
  </div>
</template>

<script setup lang="ts">
import WeddingTitle from "./WeddingTitle.vue";
</script>

<style scoped>
.wedding-info {
  background-color: #fef2f4;
  color: #211a1a;
  padding: 20px;
}
.info-section {
  margin-bottom: 20px;
}
</style>
