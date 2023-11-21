<template>
  <main class="main-page">
    <MainHero />
    <div class="decor-wrapper">
      <MainServices />
      <section class="anticovid"></section>
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
</script>

<style lang="scss" scoped></style>
