<template>
    <div>
        <p>{{ count }}</p>
        <button @click="increment">+</button>
        <nuxt-link to="/fuga">fuga</nuxt-link>
        <span> / </span>
        <nuxt-link to="/">top</nuxt-link>
    </div>
</template>

<script setup lang="ts">
const { count, increment } = useCounter()
</script>