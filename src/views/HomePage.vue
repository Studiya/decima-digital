<template>
  <main class="main-page">
    <MainHero />
    <div class="decor-wrapper">
      <MainServices />
      <AnticovidSection />
      <section class="clients"></section>
    </div>
    <section class="feedbacks"></section>
    <section class="cases"></section>
    <section class="cases"></section>
    <section class="advantages"></section>
    <section class="achievements"></section>
    <section class="blog"></section>
  </main>
</template>

<script setup>
import MainHero from '../components/sections/MainHero.vue'
import MainServices from '../components/sections/MainServices.vue'
import AnticovidSection from '../components/sections/AnticovidSection.vue'
</script>

<style lang="scss" scoped></style>
