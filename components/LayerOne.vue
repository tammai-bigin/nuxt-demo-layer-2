<template>
  <h1>[Layer-2] {{ msg ?? "Hello world!" }}</h1>
</template>

<script setup lang="ts">
defineProps({
  msg: String,
});
</script>
