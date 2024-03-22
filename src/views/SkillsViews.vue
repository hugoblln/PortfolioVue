<script setup>
import { ref } from 'vue'
import { skills } from '../assets/js/hardSkills.js'

const hardSkills = ref(skills)

</script>

<template>
  <main>
    <div v-for="skill in skills">
    <div class="card">
      <h2 class="card-title" v-html="skill.logo"></h2>
      <p class="card-content">{{ skill.language }}</p>
    </div>
    </div>
  </main>
</template>

<style scoped lang="scss">

</style>
<style scoped lang="scss">

</style>
