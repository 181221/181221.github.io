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
  max-width: 400px;
  border-radius: 4px;
}
</style>
