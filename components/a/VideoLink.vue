<template>
    <NuxtLink :to="`https://youtu.be/MnpuK0MK4yo?t=${time}`" target="_blank">
        <i><slot /></i>
    </NuxtLink>
</template>

<script setup lang="ts">
defineProps<{time: number}>();
</script>
