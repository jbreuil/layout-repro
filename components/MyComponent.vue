<script setup lang="ts">
interface Item {
  label: string
}

interface Props {
  items: Item[]
}
const { items } = defineProps<Props>()

const slides = ref<HTMLElement[] | null>(null)
</script>

<template>
  <div
  >
    <div
      v-for="(item, index) in items"
      :key="index"
      ref="slides"
    >
      {{ item.label }}
    </div>
  </div>
</template>

<style scoped>
</style>
