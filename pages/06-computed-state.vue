<template>
    <Title>count is {{ count }}</Title>

    <button @click="count++">Increment</button>

    <p>Doubled is {{ doubled }}</p>
</template>

<script setup lang="ts">
const count = ref(0);
const doubled = computed(() => count.value * 2);
</script>

<!--
See:
    - https://vuejs.org/guide/essentials/computed.html
-->
