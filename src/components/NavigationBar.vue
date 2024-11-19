<template>
  <nav class="w-full bg-black py-4 text-white flex justify-between items-center px-10">
    <a class="relative overflow-hidden rounded-lg flex justify-center items-center"
        href="/">
      <img src="../assets/images/logo.png" class="h-14">
    </a>
    <div class="flex items-center justify-evenly w-full">
      <router-link to="/fase-inicio" class="px-3 py-2 rounded-md hover:brightness-50 text-xl font-bold">Inicio</router-link>
      <router-link to="/fase-planificacion" class="px-3 py-2 rounded-md hover:brightness-50 text-xl font-bold">Planificación</router-link>
      <router-link to="/fase-desarrollo" class="px-3 py-2 rounded-md hover:brightness-50 text-xl font-bold">Diseño y desarrollo</router-link>
      <router-link to="/fase-control" class="px-3 py-2 rounded-md hover:brightness-50 text-xl font-bold">Control de Calidad e implementación</router-link>
      <router-link to="/fase-cierre" class="px-3 py-2 rounded-md hover:brightness-50 text-xl font-bold">Cierre</router-link>
    </div>
  </nav>
</template>

<script setup lang="ts">

</script>
