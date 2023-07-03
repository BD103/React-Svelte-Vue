<template>
    <p v-if="count > 1000">big</p>
    <p v-else-if="count > 500">medium</p>
    <p v-else>small</p>
</template>

<script setup lang="ts">
const count = ref(0);
</script>

<!--
See:
    - https://vuejs.org/guide/essentials/conditional.html
-->
