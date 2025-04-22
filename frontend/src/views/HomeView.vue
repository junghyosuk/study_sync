<!-- src/views/HomeView.vue -->
<script setup lang="ts">
import AppHeader from '../components/AppHeader.vue';
import AppButton from '../components/AppButton.vue';
</script>

<template>
  <AppHeader title="StudySync" />
  <main class="max-w-4xl mx-auto p-4">
    <h2 class="text-2xl font-semibold mb-4">Welcome to StudySync</h2>
    <p class="mb-4">Your personalized learning planner powered by AI.</p>
    <AppButton label="Start Learning" />
  </main>
</template>