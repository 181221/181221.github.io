<script setup lang="ts">
defineProps({
  imageUrl: String,
});
</script>

<template>
  <div class="image-text-component">
    <div class="image-container">
      <img :src="imageUrl" alt="Image" />
    </div>
    <div class="text-container">
      <p>
        Vi gleder oss til å dele denne spesielle dagen med dere, og håper dere vil være med på å gjøre vår
        bryllupsfeiring til en uforglemmelig dag!
      </p>
    </div>
  </div>
</template>

<style scoped>
.image-text-component {
  background-color: white;
}

.image-container {
  flex: 1;
  padding: 20px;
  padding-bottom: 0;
}

.image-container img {
  max-width: 400px;
  height: auto;
  border-radius: 4px;
}

.text-container {
  flex: 2;
  padding: 20px;
  font-size: larger;
  padding-top: 0;
  color: var(--graa-tekst);
}
</style>
