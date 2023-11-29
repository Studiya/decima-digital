<template>
  <header class="header">
    <div class="header__wrapper">
      <a class="header__logo" href="#">
        <svg class="header__menu-btn-icon">
          <use href="/src/assets/imgs/icons.svg#icon-logo"></use>
        </svg>
        <!-- <SvgIcon class="header__menu-btn-icon" name="icons" iconSetName="icon-logo" /> -->
      </a>
      <div class="header__content">
        <ul class="header__nav">
          <li><a href="#main-services">Magento Services</a></li>
          <li><a href="#">Who we are</a></li>
          <li><a href="#">What we do</a></li>
          <li><a href="#">Our Work</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Careers</a></li>
        </ul>
        <button
          @click="mobileMenuIsOpen = !mobileMenuIsOpen"
          type="button"
          class="header__menu-btn"
        >
          <svg class="header__menu-btn-icon">
            <use href="/src/assets/imgs/icons.svg#icon-menu-icon"></use>
          </svg>
        </button>
        <button type="button" class="header__btn btn btn-light">Get in touch</button>
      </div>
    </div>

    <div :class="{ 'is-open': mobileMenuIsOpen }" class="mobile-menu">
      <button
        @click="mobileMenuIsOpen = !mobileMenuIsOpen"
        class="mobile-menu__close-btn"
        type="button"
      >
        <svg class="header__menu-btn-icon">
          <use href="/src/assets/imgs/icons.svg#icon-cross"></use>
        </svg>
      </button>
      <div class="mobile-menu__wrapper">
        <a class="mobile-menu__logo" href="/">
          <svg class="header__menu-btn-icon">
            <use href="/src/assets/imgs/icons.svg#icon-logo"></use>
          </svg>
        </a>
        <nav class="mobile-menu__nav">
          <ul class="mobile-menu__nav-list">
            <li class="mobile-menu__nav-item">
              <a
                @click="mobileMenuIsOpen = !mobileMenuIsOpen"
                class="mobile-menu__nav-link"
                href="#main-services"
                >Magento Services</a
              >
            </li>
            <li class="mobile-menu__nav-item">
              <a
                @click="mobileMenuIsOpen = !mobileMenuIsOpen"
                class="mobile-menu__nav-link"
                href="#"
                >Who we are</a
              >
            </li>
            <li class="mobile-menu__nav-item">
              <a
                @click="mobileMenuIsOpen = !mobileMenuIsOpen"
                class="mobile-menu__nav-link"
                href="#"
                >What we do</a
              >
            </li>
            <li class="mobile-menu__nav-item">
              <a
                @click="mobileMenuIsOpen = !mobileMenuIsOpen"
                class="mobile-menu__nav-link"
                href="#"
                >Our Work</a
              >
            </li>
            <li class="mobile-menu__nav-item">
              <a
                @click="mobileMenuIsOpen = !mobileMenuIsOpen"
                class="mobile-menu__nav-link"
                href="#"
                >Blog</a
              >
            </li>
            <li class="mobile-menu__nav-item">
              <a
                @click="mobileMenuIsOpen = !mobileMenuIsOpen"
                class="mobile-menu__nav-link"
                href="#"
                >Careers</a
              >
            </li>
          </ul>
        </nav>
        <button type="button" class="mobile-menu__btn btn btn-light">Get in touch</button>
      </div>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'
// const props = defineProps(['class'])

let mobileMenuIsOpen = ref(false)
</script>

<style lang="scss" scoped></style>
