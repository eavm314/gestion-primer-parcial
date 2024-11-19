<script setup lang="ts">
import NavigationBar from "./NavigationBar.vue";
</script>

<template>
  <div class="flex flex-col min-h-screen w-full justify-start">
    <header>
      <NavigationBar />
      <RouterView />
    </header>
  </div>
</template>