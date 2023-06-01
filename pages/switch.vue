<template>
  <div>
    {{ welcome }}
      <button @click="navigateTo('/')">
        back
      </button>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: 'alternate',
})
const welcome = 'welcome'


</script>

<style scoped></style>