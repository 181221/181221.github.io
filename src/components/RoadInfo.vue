<template>
  <WeddingInfoContent>
    <WeddingSection>
      <template v-slot:title>Veibeskrivelse</template>
      <template v-slot:content>
        Viktig informasjon angående adressen
        <div class="line-break"></div>
        <a class="link-main" href="https://maps.app.goo.gl/yNYE3xu49nBjfV4s5" target="_blank"
          >Johannes Nielsens vei 67, 2007 Kjeller
        </a>
        <div class="line-break"></div>
        Vi informere om at Google maps viser feil det siste stykket. Dere vil bli vist opp den gamle gårdsveien som har
        fått en bom av vegvesenet. Dere må derfor kjøre rundt kollen. Som vist på bildet under.
      </template>
    </WeddingSection>
    <ImageBlock imageUrl="/veibeskrivelse.webp" id="image-block" />
  </WeddingInfoContent>
</template>

<script setup lang="ts">
import WeddingSection from "./WeddingSection.vue";
import WeddingInfoContent from "./WeddingInfoContent.vue";
import ImageBlock from "./ImageBlock.vue";
</script>

<style scoped>
#image-block {
  background: none;
}
</style>
