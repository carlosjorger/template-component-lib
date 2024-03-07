<script setup lang="ts">
defineProps<{ msg: string }>();
</script>

<template>
  <h1 class="message">{{ msg }}</h1>
</template>

<style scoped>
.message {
  color: #bbb;
  background-color: #222;
}
</style>
