<script setup lang="ts">

const route = useRoute()
console.log(route)
</script>

<template>
  <div>
    <h1>Task 1</h1>
    <RouterLink to="/tasks">Go to tasks</RouterLink>
  </div>
</template>
