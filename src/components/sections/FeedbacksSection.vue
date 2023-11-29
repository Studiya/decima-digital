<template>
  <section class="feedbacks">
    <div class="feedbacks__wrapper wrapper">
      <h2 class="is-head-hidden">Feedbacks</h2>
      <carousel v-bind="settings" class="feedbacks__list">
        <slide class="feedbacks__item">
          <img
            class="feedbacks__img"
            src="/src/assets/imgs/feedbacks-section/feedback-photo.webp"
            alt="Feedback photo"
          />
          <div class="feedbacks__content">
            <h3 class="feedbacks__title">Andrew Yeung</h3>
            <h4 class="feedbacks__subtitle">CEO CompAndSave</h4>
            <p class="feedbacks__text">
              “ We were looking to get a professionally built eCommerce website to improve
              conversion rate and streamline our sales, we also wanted to have some custom-tailored
              product types to attract more customers. It worked for us really good, Decima Digital
              team has proven to have deep knowledge of Magento and were able to give us what we
              needed. Decima is an effective company who I loved to work with and hope to work”
            </p>
          </div>
        </slide>
        <slide class="feedbacks__item">
          <img
            class="feedbacks__img"
            src="/src/assets/imgs/feedbacks-section/feedback-photo.webp"
            alt="Feedback photo"
          />
          <div class="feedbacks__content">
            <h3 class="feedbacks__title">Andrew Yeung</h3>
            <h4 class="feedbacks__subtitle">CEO CompAndSave</h4>
            <p class="feedbacks__text">
              “ We were looking to get a professionally built eCommerce website to improve
              conversion rate and streamline our sales, we also wanted to have some custom-tailored
              product types to attract more customers. It worked for us really good, Decima Digital
              team has proven to have deep knowledge of Magento and were able to give us what we
              needed. Decima is an effective company who I loved to work with and hope to work”
            </p>
          </div>
        </slide>
        <slide class="feedbacks__item">
          <img
            class="feedbacks__img"
            src="/src/assets/imgs/feedbacks-section/feedback-photo.webp"
            alt="Feedback photo"
          />
          <div class="feedbacks__content">
            <h3 class="feedbacks__title">Andrew Yeung</h3>
            <h4 class="feedbacks__subtitle">CEO CompAndSave</h4>
            <p class="feedbacks__text">
              “ We were looking to get a professionally built eCommerce website to improve
              conversion rate and streamline our sales, we also wanted to have some custom-tailored
              product types to attract more customers. It worked for us really good, Decima Digital
              team has proven to have deep knowledge of Magento and were able to give us what we
              needed. Decima is an effective company who I loved to work with and hope to work”
            </p>
          </div>
        </slide>
        <template #addons>
          <pagination />
        </template>
      </carousel>
    </div>
  </section>
</template>

<script setup>
import 'vue3-carousel/dist/carousel.css'
import { Carousel, Slide, Pagination } from 'vue3-carousel'

const settings = {
  wrapAround: true
}
</script>
