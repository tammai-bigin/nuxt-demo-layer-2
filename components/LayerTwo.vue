<template>
  <LayerOne :msg="title" />
  <p>{{ content }}</p>
</template>

<script setup lang="ts">
defineProps({
  title: String,
  content: String,
});
</script>
