<template>
</template>

<script setup lang="ts">
// Sin lógica de script necesaria por ahora
</script>

<style>
.contrato-contenedor {
  max-height: 500px; /* Altura máxima del contenedor */
  overflow-y: auto; /* Habilita la barra de desplazamiento vertical si el contenido excede la altura máxima */
}

.contrato-texto {
  white-space: pre-wrap; /* Respeta espacios y saltos de línea */
  word-wrap: break-word; /* Asegura que el texto no desborde el contenedor */
  font-family: monospace; /* Opcional: para un estilo de texto más tipo 'máquina de escribir' */
}

/* Aplica estilos en negrita a los textos entre asteriscos */
.contrato-texto b,
.contrato-texto strong {
  font-weight: bold;
}
</style>
