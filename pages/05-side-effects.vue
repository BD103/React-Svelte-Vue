<template>
    <!-- `<Title>` is like `<title>` but for Nuxt. -->
    <Title>count is {{ count }}</Title>

    <button @click="count++">Increment</button>
</template>

<script setup lang="ts">
const count = ref(0);
</script>

<!--
See:
    - https://vuejs.org/guide/essentials/watchers.html
    - https://vuejs.org/guide/essentials/reactivity-fundamentals.html
    - https://nuxt.com/docs/getting-started/seo-meta#components
-->
