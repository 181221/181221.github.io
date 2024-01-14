<script setup lang="ts">
defineProps({
  imageUrl: String,
});
</script>

<template>
  <div class="image-container">
    <img :src="imageUrl" alt="Image" />
  </div>
</template>

<style scoped>
.image-container {
  background-color: white;
  padding: 20px;
}
.image-container img {
  max-width: 100%;
  border-radius: 4px;
}

@media (min-width: 768px) {
  .image-container img {
    max-width: 400px;
    height: auto;
  }
}
</style>
