<template>
  <h2>Hello {{ header }}</h2>
</template>

<script setup lang="ts">
const { header } = defineProps<{ header: string }>();
</script>
