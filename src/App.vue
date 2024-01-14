<script setup lang="ts">
import WeddingHeader from "./components/WeddingHeader.vue";
import ImageTextBlock from "./components/ImageTextBlock.vue";
import WeddingInfoBlock from "./components/WeddingInfoBlock.vue";
import ImageBlock from "./components/ImageBlock.vue";
import WeddingFooter from "./components/WeddingFooter.vue";
import RoadInfo from "./components/RoadInfo.vue";
</script>

<template>
  <WeddingHeader />
  <ImageTextBlock imageUrl="/pogcirland.jpg" />
  <WeddingInfoBlock />
  <ImageBlock imageUrl="/pederogcecilie.jpg" />
  <RoadInfo />
  <WeddingFooter />
</template>

<style scoped></style>
