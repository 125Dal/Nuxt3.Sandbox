<template>
  <div>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">
const { data } = await useFetch('/api/v1/hello')
console.log(data.value.data)
</script>
