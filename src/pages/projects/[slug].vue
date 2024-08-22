<script setup lang="ts">

const route = useRoute('/projects/[slug]')
console.log(route)
</script>

<template>
  <div>
    <h1>Project {{ route.params?.slug }}</h1>
    <RouterLink to="/projects">Go to projects</RouterLink>
  </div>
</template>
