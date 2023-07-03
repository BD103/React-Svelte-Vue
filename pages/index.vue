<template>
    <h1>React vs. Svelte vs. Vue</h1>

    <ol>
        <li>
            <NuxtLink to="/01-state">State</NuxtLink>
            <AVideoLink :time="102"> (1:42)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/02-props">Props</NuxtLink>
            <AVideoLink :time="139"> (2:19)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/03-children">Children</NuxtLink>
            <AVideoLink :time="168"> (2:49)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/04-lifecycle">Lifecycle</NuxtLink>
            <AVideoLink :time="196"> (3:16)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/05-side-effects">Side-Effects</NuxtLink>
            <AVideoLink :time="223"> (3:43)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/06-computed-state">Computed State</NuxtLink>
            <AVideoLink :time="263"> (4:23)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/07-conditional-logic">Conditional Logic</NuxtLink>
            <AVideoLink :time="297"> (4:57)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/08-loops">Loops</NuxtLink>
            <AVideoLink :time="357"> (5:56)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/09-shared-state">Shared State</NuxtLink>
            <AVideoLink :time="384"> (6:23)</AVideoLink>
        </li>
        <li>
            <NuxtLink to="/10-promises">Promises</NuxtLink>
            <AVideoLink :time="456"> (7:34)</AVideoLink>
        </li>
    </ol>
</template>

<script setup lang="ts">
// Disable the "Go back home..." message.
definePageMeta({
    layout: "empty",
});

useHead({
    title: "React vs. Svelte vs. Vue",
});
</script>
