<template>
  <section class="cases">
    <div class="cases__wrapper wrapper">
      <h2 class="cases__title">Case studies</h2>
      <Carousel v-bind="settings" class="cases__list">
        <Slide class="cases__slide">
          <div class="cases__item">
            <img
              class="cases__item-img"
              src="src/assets/imgs/cases-section/case-1.webp"
              alt="Myriad Beauty Case Photo"
            />
            <div class="cases__item-content">
              <h3 class="cases__item-title">Myriad Beauty</h3>
              <p class="cases__item-descr">
                How Myriad Beauty gained customer loyalty by enhancing Magento 2 performance
              </p>
              <div class="cases__item-more">
                <a href="#">Read more ></a>
              </div>
            </div>
            <div class="cases__item-logo">
              <img src="src/assets/imgs/cases-section/myriad-logo.svg" alt="myriad-logo" />
            </div>
          </div>
        </Slide>
        <Slide class="cases__slide">
          <div class="cases__item">
            <img
              class="cases__item-img"
              src="src/assets/imgs/cases-section/case-2.webp"
              alt="Adobe Case Photo"
            />
            <div class="cases__item-content">
              <h3 class="cases__item-title">Adobe</h3>
              <p class="cases__item-descr">
                How Myriad Beauty gained customer loyalty by enhancing Magento 2 performance
              </p>
              <div class="cases__item-more">
                <a href="#">Read more ></a>
              </div>
            </div>
            <div class="cases__item-logo">
              <img src="src/assets/imgs/cases-section/adobe-logo.svg" alt="adobe-logo" />
            </div>
          </div>
        </Slide>
        <Slide class="cases__slide">
          <div class="cases__item">
            <img
              class="cases__item-img"
              src="src/assets/imgs/cases-section/case-1.webp"
              alt="Myriad Beauty Case Photo"
            />
            <div class="cases__item-content">
              <h3 class="cases__item-title">Myriad Beauty</h3>
              <p class="cases__item-descr">
                How Myriad Beauty gained customer loyalty by enhancing Magento 2 performance
              </p>
              <div class="cases__item-more">
                <a href="#">Read more ></a>
              </div>
            </div>
            <div class="cases__item-logo">
              <img src="src/assets/imgs/cases-section/myriad-logo.svg" alt="myriad-logo" />
            </div>
          </div>
        </Slide>
        <Slide class="cases__slide">
          <div class="cases__item">
            <img
              class="cases__item-img"
              src="src/assets/imgs/cases-section/case-2.webp"
              alt="Adobe Case Photo"
            />
            <div class="cases__item-content">
              <h3 class="cases__item-title">Adobe</h3>
              <p class="cases__item-descr">
                How Myriad Beauty gained customer loyalty by enhancing Magento 2 performance
              </p>
              <div class="cases__item-more">
                <a href="#">Read more ></a>
              </div>
            </div>
            <div class="cases__item-logo">
              <img src="src/assets/imgs/cases-section/adobe-logo.svg" alt="adobe-logo" />
            </div>
          </div>
        </Slide>
        <template #addons>
          <Navigation />
        </template>
      </Carousel>
      <button class="cases__btn btn btn-orange" type="button">Learn More</button>
    </div>
  </section>
</template>

<script setup>
import 'vue3-carousel/dist/carousel.css'
import { Carousel, Slide, Navigation } from 'vue3-carousel'

const settings = {
  itemsToShow: 2,
  itemsToScroll: 2,
  snapAlign: 'start'
}
</script>
