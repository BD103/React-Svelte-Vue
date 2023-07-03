<template>
    <SharedStateCounter />
</template>

<script setup lang="ts">
const count = ref(0);

function incrementCount() {
    count.value++;
}

provide("count", {
    count,
    incrementCount,
});
</script>

<!--
See:
    - https://vuejs.org/guide/components/provide-inject.html
    - https://vuejs.org/guide/components/provide-inject.html#working-with-reactivity
-->
