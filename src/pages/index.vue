<script setup lang="ts">
usePageStore().pageData.title = 'Home page'
</script>

<template>
  <div>
    <h1>Home Page</h1>
    <RouterLink to="/projects">Go to projects page</RouterLink>
  </div>
</template>
