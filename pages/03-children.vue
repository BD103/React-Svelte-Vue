<template>
    <NavBar>
        <!-- #header is short for v-slot:header. -->
        <template #header>
            My Website
        </template>

        <!-- This will be put in the default slot. -->
        <ul>
            <li>Home</li>
            <li>About</li>
            <li>Contact</li>
        </ul>

        <template #footer>
            <button>Login</button>
        </template>
    </NavBar>
</template>

<!--
See:
    - https://vuejs.org/guide/components/slots.html
    - https://vuejs.org/guide/components/slots.html#named-slots
-->
