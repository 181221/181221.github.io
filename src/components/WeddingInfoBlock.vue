<template>
  <WeddingInfoContent>
    <WeddingSection>
      <template v-slot:title>Den store dagen</template>
      <template v-slot:content>
        Vi gleder oss til å feire vår store dag sammen med dere! Vår bryllupsfeiring begynner klokken 12.00 med
        forskjellige arrangementer gjennom dagen. Vielsen vil finne sted kl. 13.00 i Kjeller Gaards hage. Kl. 17.00 vil
        det være en herlig middag, taler og feiring i Kjeller Gaards selskapslokaler. Senere på kvelden vil det være
        musikk og dans for de som ønsker å fortsette festen. Vi håper du vil være med oss gjennom hele dagen, men hvis
        du ikke kan delta på hele programmet, setter vi pris på at du kan delta på det som passer for deg. Din
        tilstedeværelse vil glede oss uansett når du kan komme. Takk for at dere deler denne spesielle dagen med oss, og
        vi ser frem til å feire sammen med dere!
      </template>
    </WeddingSection>
    <WeddingSection>
      <template v-slot:title>Antrekk</template>
      <template v-slot:content>
        Vi ønsker at gjestene kler seg pent, gjerne i formelle antrekk som dress eller kjole. Vi setter stor pris på om
        gjester unngår å gå i hvitt. Store deler av dagen vil foregå ute på gressplen, så bruk gjerne sko man kan gå på
        gress med. Dersom det blir regn anbefaler vi også å ha med paraply, ettersom selve middagen blir ute i hagen
        under telt og det ikke er tak mellom hageteltet og selve huset.
      </template>
    </WeddingSection>
    <WeddingSection>
      <template v-slot:title>Våre Toastmastere - Sigurd og Jeanette</template>
      <template v-slot:content>
        Vi er begeistret for å introdusere de utrolige toastmasterne for vår store dag - Sigurd og Jeanette! Disse to
        fantastiske menneskene vil sørge for at bryllupet vårt blir en uforglemmelig opplevelse fylt med latter, glede
        og kjærlighet.
      </template>
    </WeddingSection>
    <WeddingSection>
      <template v-slot:title>Overnatting</template>
      <template v-slot:content>
        Kjeller Gård har en avtale med Quality Hotel Olavsgaard som ligger 5 minutter med bil fra Kjeller Gård. De kan
        tilby enkeltrom inkludert frokost for kr 1 341,- og dobbeltrom inkludert frokost for kr 1 701,-. Rommene kan
        bookes ved å sende mail til
        <a class="link-main" href="mail:to:booking@olavsgaard.no">Quality Hotel Olavsgaard</a>. Ved booking, informer
        gjerne om at det er i forbindelse med bryllupet vårt den helgen. Det finnes også andre muligheter for
        overnatting for eksempel i Lillestrøm eller Oslo.
      </template>
    </WeddingSection>

    <WeddingSection>
      <template v-slot:title>Gaveliste</template>
      <template v-slot:content>
        Vi ser frem til å dele vår spesielle dag med dere, og deres deltakelse er den største gaven for oss. For de som
        ønsker å gi en fysisk gave, har vi opprettet to gavelister – én hos
        <a
          class="link-main"
          href="https://www.illumsbolighus.no/on/demandware.store/Sites-illums_bolighus_no-Site/nb_NO/GiftRegistry-ShowOthers?id=f1edcd6274d920b80e0debf154"
          target="_blank"
          >Illums Bolighus</a
        >
        og en annen hos
        <a class="link-main" href="https://www.tilbords.no/bryllup/vis-liste/133640" target="_blank">Tilbords</a>
        <div class="line-break"></div>
        Samtidig verdsetter vi også økonomisk støtte for å hjelpe oss med å realisere våre drømmer om en uforglemmelig
        bryllupsreise i Latin Amerika, etterfulgt av feiring i Chile. Ønsker du å bidra økonomisk, kan dette gjøres
        gjennom
        <a class="link-main" href="https://stor.stas.app/gave/peder-og-cecilie" target="_blank">Stas</a>
        <div class="line-break"></div>
        Vi ser frem til å skape minner sammen og er takknemlige for enhver form for gave. Takk for deres kjærlighet og
        støtte!
      </template>
    </WeddingSection>
  </WeddingInfoContent>
</template>

<script setup lang="ts">
import WeddingSection from "./WeddingSection.vue";
import WeddingInfoContent from "./WeddingInfoContent.vue";
</script>
