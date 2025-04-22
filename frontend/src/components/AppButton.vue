<!-- src/components/AppButton.vue -->
<script setup lang="ts">
defineProps<{
  label: string;
}>();
</script>

<template>
  <button
    class="bg-blue-500 text-white px-4 py-2 rounded-md hover:bg-blue-600 transition-colors"
  >
    {{ label }}
  </button>
</template>