<template>
    <SharedStateCounter />
</template>

<script setup lang="ts">
const count = ref(0);

function incrementCount() {
    count.value++;
}

// It is recommended that the provider is the only component that mutates the value.
// Because of this, we can pass in an update function that others can call.
provide("count", {
    count,
    incrementCount,
});
</script>

<!--
See:
    - https://vuejs.org/guide/components/provide-inject.html
    - https://vuejs.org/guide/components/provide-inject.html#working-with-reactivity
    - https://vuejs.org/guide/typescript/composition-api.html#typing-provide-inject
-->
