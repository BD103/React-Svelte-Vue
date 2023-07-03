<template>
    <!-- `key` is a hint for Vue's VDOM. -->
    <p v-for="item in items" :key="item.id">{{ item.name }}</p>
</template>

<script setup lang="ts">
const items = [
    { id: 1, name: "foo" },
    { id: 2, name: "bar" },
    { id: 3, name: "baz" },
];
</script>

<!--
See:
    - https://vuejs.org/guide/essentials/list.html
    - https://vuejs.org/guide/essentials/list.html#maintaining-state-with-key
    - https://vuejs.org/api/built-in-special-attributes.html#key
-->
