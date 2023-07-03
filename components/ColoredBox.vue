<template>
    You picked: {{ color }}
</template>

<script setup lang="ts">
// This allows us to write `<ColoredBox color="blue" />`.
defineProps<{
    color: string,
}>();
</script>
