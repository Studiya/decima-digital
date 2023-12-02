<script setup>
import { defineAsyncComponent } from 'vue'

const props = defineProps({
  name: {
    type: String,
    required: true,
    defualt: ''
  },
  setSymbol: {
    type: String,
    required: false,
    default: ''
  }
})

const icon = defineAsyncComponent(() => import(`/src/assets/imgs/${props.name}.svg`))
</script>

<template>
  <!-- <component :is="icon" /> -->
  <icon />
</template>
