<template>
  <div>
    {{ welcome }}

  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'alternate',
})
const welcome = 'welcome back'


</script>

<style scoped></style>