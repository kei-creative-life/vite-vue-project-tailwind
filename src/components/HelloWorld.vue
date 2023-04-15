<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <div class="p-4">
    <h1 class="text-3xl">
      {{ msg }}
    </h1>
    <button class="text-white bg-blue-500 py-2 px-3">
      Primary
    </button>
  </div>
</template>

<style scoped></style>
