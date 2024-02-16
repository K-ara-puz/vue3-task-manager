<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav class="flex gap-5 font-bold border-b-2 border-gray-700 mb-5 pb-2">
        <RouterLink to="/" class="text-green-700 hover:text-blue-400">Home</RouterLink>
        <RouterLink to="/about" class="text-green-700 hover:text-blue-400">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>
