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
      <div class="decor-wrapper__left"></div>
      <div class="decor-wrapper__right"></div>
    </div>
    <AdvantagesSection />
    <AchievmentsSection />
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
import AdvantagesSection from '../components/sections/AdvantagesSection.vue'
import AchievmentsSection from '../components/sections/AchievmentsSection.vue'
</script>

<style lang="scss" scoped></style>
