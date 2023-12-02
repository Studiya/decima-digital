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
    defualt: ''
  }
})

const icon = defineAsyncComponent(() => import(`./imgs/${props.name}.svg`))
</script>

<template>
  <!-- <component :is="icon" /> -->
  <icon />
</template>
