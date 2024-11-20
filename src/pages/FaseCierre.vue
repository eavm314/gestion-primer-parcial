<template>
  <div class="p-4 bg-white">
      
      <div class="p-4 border-4 border-gray-500 rounded-lg mb-6">
          <h2 class="text-3xl font-bold mb-4 text-center">Carta de Cierre del Proyecto</h2>
          <h3 class="text-center text-lg font-bold pb-5">Desarrollo de la Plataforma Web de EXPOHOGAR</h3>
          <div class="grid gap-4">
              
              <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
                  <h2 class="text-lg font-semibold mb-2">Entregables del Proyecto</h2>
                  <li>Frontend y Backend del Sitio Web: página principal, sistema de inscripción, galerías multimedia.</li>
                  <li>Plataforma de Administración: módulo de gestión de contenido y galería multimedia.</li>
                  <li>Pruebas y Validación: usabilidad y accesibilidad en múltiples dispositivos.</li>
              </div>

              <!-- Servidor y Hosting -->
              <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
                  <h2 class="text-lg font-semibold mb-2">Servidor y Hosting</h2>
                  <li>Servidor: Arquitectura serverless utilizando AWS ApiGateway y Cloudfront.</li>
                  <li>Hosting: Implementación en AWS S3 como SPA con CDN.</li>
                  <li>Dominio: Configuración en "expohogar.com".</li>
                  <li>Base de Datos: Mongo Atlas para almacenamiento.</li>
              </div>

              <!-- Documentación Entregada -->
              <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
                  <h2 class="text-lg font-semibold mb-2">Documentación Entregada</h2>
                  <li>Manual de Usuario: Uso general para visitantes.</li>
                  <li>Manual de Administrador: Gestión de contenido y resolución de problemas comunes.</li>
                  <li>Manual del Sistema: Documentación técnica para desarrolladores y mantenimiento.</li>
              </div>

              <!-- Manuales -->
              <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
                  <h2 class="text-lg font-semibold mb-2">Manuales Detallados</h2>
                  <h3 class="text-md font-semibold">Manual de Usuario</h3>
                  <li>Guía para explorar eventos, registrarse e interactuar con las secciones.</li>
                  <li>Incluye capturas de pantalla con descripciones detalladas.</li>
                  
                  <h3 class="text-md font-semibold">Manual de Administrador</h3>
                  <li>Gestión de eventos, expositores y galerías multimedia.</li>
                  <li>Resolución de problemas frecuentes.</li>

                  <h3 class="text-md font-semibold">Manual del Sistema</h3>
                  <li>Configuración técnica del servidor y dependencias.</li>
                  <li>Credenciales necesarias para la administración de AWS y Mongo Atlas.</li>
                  <li>Pasos detallados para expandir o modificar el sistema.</li>
              </div>

              <!-- Mantenimiento -->
              <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
                  <h2 class="text-lg font-semibold mb-2">Mantenimiento</h2>
                  <li>Corrección de errores y ajustes durante 30 días posteriores a la entrega.</li>
                  <li>Resolución de problemas críticos reportados por usuarios finales.</li>
              </div>

              
              <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
                  <h2 class="text-lg font-semibold mb-2">Post-Mantenimiento</h2>
                  <li>Servicios adicionales sujetos a nuevos acuerdos.</li>
                  <li>Expansión de funcionalidades y optimización para tecnologías futuras.</li>
              </div>
          </div>
      </div>

      <!-- Carta de Aceptación -->
      <div class="p-4 border-4 border-gray-500 rounded-lg">
          <h2 class="text-3xl font-semibold mb-4 text-center">Carta de Aceptación</h2>
          <div class="grid gap-4">
              <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
                  <h3 class="text-lg font-semibold mb-2">Conformidad del Cliente</h3>
                  <li>El cliente revisará los entregables y firmará en señal de conformidad.</li>
                  <li>Se incluye espacio para las firmas de los responsables de COREWEB y EXPOHOGAR.</li>
              </div>
              <div class="text-center">
            <p>COREWEB Jhosias Laguna Responsable del Proyecto</p>
            <div class="border-t mt-4 w-48 mx-auto"></div>
        </div>
        <div class="text-center">
            <p>EXPOHOGAR Sr.Cliente Responsable del Proyecto</p>
            <div class="border-t mt-4 w-48 mx-auto"></div>
        </div>
          </div>
      </div>
  </div>
  

</template>

<script setup lang="ts">
</script>

<style>
</style>
