<template>
    <button @click="count++">
        Count is {{ count }}
    </button>
</template>

<script setup lang="ts">
// ref() is a reactive value.
const count = ref(0);
</script>

<!--
See:
    - https://vuejs.org/guide/essentials/template-syntax.html
    - https://vuejs.org/guide/essentials/reactivity-fundamentals.html
    - https://vuejs.org/guide/essentials/event-handling.html
-->
