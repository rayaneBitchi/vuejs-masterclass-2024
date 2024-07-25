<script setup lang="ts">
import { RouterLink } from 'vue-router'
import { useRoute } from 'vue-router'
// const route = useRoute()s
</script>

<template>
  <div>
    <h1>Projects Page</h1>
    <RouterLink :to="{name: '/projects/[id]', params: {'id': 1}}">Go to project 1</RouterLink>
    <br />
    <RouterLink to="/">Back to Home</RouterLink>
  </div>
</template>
