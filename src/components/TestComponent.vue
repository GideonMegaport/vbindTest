<script lang="ts" setup>
defineProps<{
  color: string
  class: string
  style: string
}>()
</script>

<template>
  <div :color :class :style></div>
</template>
