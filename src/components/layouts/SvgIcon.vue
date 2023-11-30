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

const icon = defineAsyncComponent(
  () => import(`/src/assets/imgs/${props.name}.svg#${props.setSymbol}`)
)
</script>

<template>
  <component :is="icon" />
</template>
