<template>
  <Head>
    <Title>Hestara - Buat Aplikasi Tanpa Kode Program</Title>
    <Meta name="description" content="Buat aplikasi tanpa kode program" />
  </Head>
  <HeroSection />
  <FeaturesSection />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import HeroSection from "~~/components/Home/HeroSection.vue";
import FeaturesSection from "~~/components/Home/FeaturesSection.vue";

export default defineComponent({
  setup() {},
  components: { HeroSection, FeaturesSection },
});
</script>
