<template>
  <section class="main-partners">
    <div class="main-partners__wrapper wrapper">
      <h2 class="main-partners__title">Companies who trust us</h2>
      <p class="main-partners__subtitle">We've helped many companies reach their business goals</p>
      <ul class="main-partners__list">
        <li class="main-partners__item" v-for="partner in partnersList" :key="partner.id">
          <a :href="partner.link"><img :src="partner.image" :alt="partner.alt" /></a>
        </li>
      </ul>
    </div>
  </section>
</template>

<script setup>
let partnersList = [
  {
    id: 0,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/magento.svg',
    alt: 'Magento partner'
  },
  {
    id: 1,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/adobe.svg',
    alt: 'Adobe partner'
  },
  {
    id: 2,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/Logotech.svg',
    alt: 'Logotech partner'
  },
  {
    id: 3,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/google.svg',
    alt: 'Google partner'
  },
  {
    id: 4,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/microsoft.svg',
    alt: 'Microsoft partner'
  },
  {
    id: 5,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/afterpay.svg',
    alt: 'Afterpay partner'
  },
  {
    id: 6,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/save.svg',
    alt: 'Comp and Save partner'
  },
  {
    id: 7,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/Zoho.svg',
    alt: 'Zoho partner'
  },
  {
    id: 8,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/Freshfarm.svg',
    alt: 'Freshfarm.it'
  },
  {
    id: 9,
    link: '#',
    image: 'src/assets/imgs/main-partners-section/myriad.svg',
    alt: 'Myriad Beauty'
  }
]
</script>
