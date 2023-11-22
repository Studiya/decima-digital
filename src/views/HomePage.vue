<template>
  <main class="main-page">
    <MainHeroSection />
    <div class="decor-wrapper decor-wrapper_first">
      <MainServicesSection />
      <AnticovidSection />
    </div>
    <div class="decor-wrapper decor-wrapper_second">
      <MainPartnersSection />
      <FeedbacksSection />
      <CasesSection />
    </div>
    <section class="advantages"></section>
    <section class="achievements"></section>
    <section class="blog"></section>
  </main>
</template>

<script setup>
import MainHeroSection from '../components/sections/MainHero.vue'
import MainServicesSection from '../components/sections/MainServices.vue'
import AnticovidSection from '../components/sections/AnticovidSection.vue'
import MainPartnersSection from '../components/sections/MainPartners.vue'
import FeedbacksSection from '../components/sections/FeedbacksSection.vue'
import CasesSection from '../components/sections/CasesSection.vue'
</script>

<style lang="scss" scoped></style>
