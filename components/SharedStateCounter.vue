<template>
    <button @click="incrementCount">Count is {{ count }}</button>
</template>

<script setup>
const { count, incrementCount } = inject("count");
</script>
