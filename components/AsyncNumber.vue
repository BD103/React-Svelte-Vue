<template>
    <p>The number is {{ number }}</p>
</template>

<script setup lang="ts">
const number = await Promise.resolve(69);
</script>
