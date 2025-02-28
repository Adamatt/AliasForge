<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="text-blue-500">{{ msg }}</h1>
    <h3>
      You’ve successfully created a project with
      <div class="i-logos-vue text-3xl" /> +
      <a href="https://vuejs.org/" target="_blank" rel="noopener">Vue 3</a>. What's next?
    </h3>
  </div>
</template>
