<script setup>
import { RouterLink } from 'vue-router'

</script>

<template>
    <aside>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/skills">Skills</RouterLink>
        <RouterLink to="/experience">Experience</RouterLink>
        <RouterLink to="/contact">Contact</RouterLink>
    </aside>
</template>

<style scoped lang="scss">
@import './src/assets/css/aside.scss';
</style>