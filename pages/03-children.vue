<template>
    <NavBar>
        <template #header>
            My Website
        </template>

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
