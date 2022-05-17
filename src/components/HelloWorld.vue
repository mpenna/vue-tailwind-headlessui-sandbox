<script setup>
defineProps({
  msg: String
})
</script>

<template>
  <h1 class="text-3xl font-semibold">
    {{ msg }}
  </h1>
</template>
