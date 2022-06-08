<template>
    <div>
        <p>{{ count }}</p>
        <button @click="decrement">-</button>
        <nuxt-link to="/hoge">hoge</nuxt-link>
        <span> / </span>
        <nuxt-link to="/">top</nuxt-link>
    </div>
</template>

<script setup lang="ts">
const { count, decrement } = useCounter()
</script>