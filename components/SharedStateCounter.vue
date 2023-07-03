<template>
    <button @click="incrementCount">Count is {{ count }}</button>
</template>

<!--
Note the lack of `lang="ts"`.
This is because typing `Ref`s and functions is annoying, and does not contribute to this example.
So instead, we simply disable type checking.
-->
<script setup>
const { count, incrementCount } = inject("count");
</script>
