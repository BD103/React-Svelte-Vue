<template>
    You picked: {{ color }}
</template>

<script setup lang="ts">
defineProps<{
    color: string,
}>();
</script>
