<script setup>
import { defineAsyncComponent } from 'vue'

const props = defineProps({
  name: {
    type: String,
    required: true
  },
  setSymbol: {
    type: String,
    required: false
  }
})

// feel free to update this with an svg directory of your choice
const icon = defineAsyncComponent(
  () => import(/* @vite-ignore */ `/src/assets/imgs/${props.name}.svg#${props.setSymbol}`)
)
</script>

<template>
  <component :is="icon" />
</template>
