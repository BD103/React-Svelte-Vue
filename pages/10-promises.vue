<template>
    <!-- `<Suspense>` orchestrates asynchronous components. -->
    <Suspense>
        <!-- This is an asynchronous component. -->
        <AsyncNumber />

        <template #fallback>
            Loading...
        </template>
    </Suspense>
</template>

<script setup lang="ts">
onErrorCaptured(err => {
    // Handle error here...
});
</script>

<!--
See:
    - https://vuejs.org/guide/built-ins/suspense.html
    - https://vuejs.org/guide/built-ins/suspense.html#loading-state
    - https://vuejs.org/api/composition-api-lifecycle.html#onerrorcaptured
    - https://vuejs.org/guide/components/async.html
-->
