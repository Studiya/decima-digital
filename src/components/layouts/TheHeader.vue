<template>
  <header class="header">
    <div class="header__wrapper">
      <a class="header__logo" href="#">
        <img :src="logoSrc" alt="logo" />
      </a>
      <div class="header__inner">
        <ul class="header__nav">
          <li><a href="#">Magento Services</a></li>
          <li><a href="#">Who we are</a></li>
          <li><a href="#">What we do</a></li>
          <li><a href="#">Our Work</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Careers</a></li>
        </ul>
        <button type="button" class="btn btn-light">Get in touch</button>
      </div>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'
let logoSrc = ref('src/assets/imgs/header/logo-main.svg')
// const props = defineProps(['class'])
</script>

<style lang="scss" scoped></style>
