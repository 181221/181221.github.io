<script setup lang="ts">
import WeddingHeader from "./components/WeddingHeader.vue";
import ImageTextBlock from "./components/ImageTextBlock.vue";
import WeddingInfo from "./components/WeddingInfo.vue";
import ImageBlock from "./components/ImageBlock.vue";
import WeddingFooter from "./components/WeddingFooter.vue";
</script>

<template>
  <WeddingHeader />
  <ImageTextBlock imageUrl="/otto.jpg" />
  <WeddingInfo />
  <ImageBlock imageUrl="/otto.jpg" />
  <WeddingFooter />
</template>

<style scoped></style>
