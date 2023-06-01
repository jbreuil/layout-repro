<template>
  <div>
    {{ hello }}
      <button @click="navigateTo('/switch')">
        Switch
      </button>
      <MyComponent :items="items"></MyComponent>
  </div>
</template>

<script setup lang="ts">
const hello = 'hello world'
const items = [{label: '1'},{label: '2'},{label: '3'},{label: '4'},{label: '5'},]
</script>

<style scoped></style>