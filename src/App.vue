<script setup>
import { useHead } from "@vueuse/head";
import HeroSection from "./components/HeroSection.vue";
import IncentivesSection from "./components/IncentivesSection.vue";
import RegisterForm from "./components/RegisterForm.vue";

useHead({
  title: "Nutrily",
  meta: [
    {
      name: "description",
      content:
        "Nutrily es una plataforma para ayudar a las personas a crear sus propias dietas saludables.",
    },
  ],
});
</script>

<template>
  <HeroSection />
  <IncentivesSection />
  <RegisterForm />
</template>
