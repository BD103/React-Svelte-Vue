<template>
    <p>The number is {{ number }}</p>
</template>

<script setup lang="ts">
// `await` automatically converts this component to be asynchronous.
const number = await Promise.resolve(69);
</script>
