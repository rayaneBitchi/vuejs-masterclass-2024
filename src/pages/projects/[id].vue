<script setup lang="ts">
import { RouterLink } from 'vue-router'
import { useRoute } from 'vue-router'

const route = useRoute()
console.log(route)
</script>

<template>
  <div>
    <h1>Project 1</h1>
    <RouterLink to="/projects">Go to projects</RouterLink>
  </div>
</template>
