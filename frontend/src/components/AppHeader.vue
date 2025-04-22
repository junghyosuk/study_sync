<!-- src/components/AppHeader.vue -->
<script setup lang="ts">
defineProps<{
  title: string;
}>();
</script>

<template>
  <header class="bg-blue-600 text-white p-4 shadow-md">
    <h1 class="text-2xl font-bold">{{ title }}</h1>
  </header>
</template>