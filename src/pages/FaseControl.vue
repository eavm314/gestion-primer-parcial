<template>
  <div class="p-4 bg-white"></div>
  <div class="p-4 border-4 border-gray-500 rounded-lg mb-6">
    <h2 class="text-3xl font-bold mb-4 text-center">Fase de Control de Calidad e Implementación</h2>
    <div class="grid gap-4">
      <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
        <h2 class="text-lg font-semibold mb-2">Tipos de prueba</h2>
        <li>Pruebas de Funcionalidad: Verificación de módulos como inscripciones, galerías, y notificaciones.</li>
        <li>Pruebas de Compatibilidad: Verificación de funcionamiento en diferentes navegadores y dispositivos.</li>
        <li>Pruebas de Rendimiento: Análisis de tiempo de carga y simulación de tráfico.</li>
        <li>Pruebas de Seguridad: Revisión de vulnerabilidades en datos personales y conexiones seguras.</li>
        <li>Pruebas de Usabilidad: Evaluación de la experiencia de usuario (UX) y retroalimentación interna.</li>
      </div>
      <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
        <h2 class="text-xl font-bold mx-8">Herramientas</h2>
        <div class="flex flex-row justify-center">
          <img src="../assets/images/pruebas/Selenium.png" class="my-4 w-80 h-40 object-contain" />
          <img src="../assets/images/pruebas/zap.jpg" class="my-4 w-80 h-40 object-contain" />
        </div>
      </div>
      <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
        <h2 class="text-xl font-bold mx-8">Selección de Servidor, Hosting y Despliegue</h2>
        <h3 class="text-xl font-bold mx-8">Servicios de Hosting</h3>
        <li>Frontend: Amazon S3 para archivos estáticos y Amazon CloudFront como CDN para mejorar la entrega de
          contenido.</li>
        <li>Gestión de Dominios: Amazon Route 53 para la gestión de DNS.</li>
        <li>Backend y Funciones Serverless: AWS Lambda para ejecutar funciones backend y API Gateway para exponer APIs.
        </li>
        <li>Base de Datos: MongoDB Atlas para el almacenamiento seguro y escalable de datos.</li>

        <h3 class="text-xl font-bold mx-8">Proceso de Despliegue</h3>
        <li>El frontend se desplegará en S3 y se distribuirá mediante CloudFront.</li>
        <li>Las funciones Lambda se conectarán a MongoDB Atlas y se gestionarán con AWS CLI o CodePipeline para asegurar
          un flujo CI/CD.</li>
        <li>Monitoreo con AWS CloudWatch para asegurar el buen funcionamiento y escalabilidad automática.</li>
      </div>
      <div class="border border-gray-500 p-4 rounded-lg flex flex-col gap-2">
        <h2 class="text-xl font-bold mx-8">Análisis de Alternativas de Hosting</h2>
        <div class="flex flex-row justify-center">
          <img src="../assets/images/pruebas/azure.png" class="my-4 w-80 h-40 object-contain" />
          <img src="../assets/images/pruebas/aws.png" class="my-4 w-80 h-40 object-contain" />
          <img src="../assets/images/pruebas/google cloud.png" class="my-4 w-80 h-40 object-contain" />
        </div>

        <table class="min-w-full table-auto border-collapse border border-gray-500 mt-4">
          <thead>
            <tr class="bg-blue-200">
              <th class="border px-4 py-2 text-left">Servicio</th>
              <th class="border px-4 py-2 text-left">AWS</th>
              <th class="border px-4 py-2 text-left">Google Cloud</th>
              <th class="border px-4 py-2 text-left">Azure</th>
            </tr>
          </thead>
          <tbody>
            <tr class="bg-gray-100">
              <td class="border px-4 py-2">Almacenamiento estático</td>
              <td class="border px-4 py-2">Amazon S3</td>
              <td class="border px-4 py-2">Google Cloud Storage</td>
              <td class="border px-4 py-2">Azure Blob Storage</td>
            </tr>
            <tr>
              <td class="border px-4 py-2">Precio por GB de almacenamiento</td>
              <td class="border px-4 py-2">$0.023/GB (Standard Storage)</td>
              <td class="border px-4 py-2">$0.020/GB (Standard Storage)</td>
              <td class="border px-4 py-2">$0.0184/GB (Hot Blob Storage)</td>
            </tr>
            <tr>
              <td class="border px-4 py-2">Costo por GB de transferencia de datos</td>
              <td class="border px-4 py-2">$0.09 por GB</td>
              <td class="border px-4 py-2">$0.12 por GB</td>
              <td class="border px-4 py-2">$0.087 por GB</td>
            </tr>
            <tr class="bg-gray-100">
              <td class="border px-4 py-2">Entrega de contenido (CDN)</td>
              <td class="border px-4 py-2">Amazon CloudFront</td>
              <td class="border px-4 py-2">Google Cloud CDN</td>
              <td class="border px-4 py-2">Azure CDN</td>
            </tr>
            <tr>
              <td class="border px-4 py-2">Precio por GB de transferencia</td>
              <td class="border px-4 py-2">$0.085 por GB</td>
              <td class="border px-4 py-2">$0.08 por GB</td>
              <td class="border px-4 py-2">$0.087 por GB</td>
            </tr>
            <tr class="bg-gray-100">
              <td class="border px-4 py-2">Funciones Serverless</td>
              <td class="border px-4 py-2">AWS Lambda</td>
              <td class="border px-4 py-2">Google Cloud Functions</td>
              <td class="border px-4 py-2">Azure Functions</td>
            </tr>
            <tr>
              <td class="border px-4 py-2">Costo por invocación</td>
              <td class="border px-4 py-2">$0.20 por 1 millón de invocaciones</td>
              <td class="border px-4 py-2">$0.40 por 1 millón de invocaciones</td>
              <td class="border px-4 py-2">$0.20 por 1 millón de invocaciones</td>
            </tr>
            <tr>
              <td class="border px-4 py-2">Costo por duración de ejecución</td>
              <td class="border px-4 py-2">$0.00001667 por GB-segundo (por cada 100 ms)</td>
              <td class="border px-4 py-2">$0.0000025 por GB-segundo (por cada 100 ms)</td>
              <td class="border px-4 py-2">$0.000016 por GB-segundo (por cada 100 ms)</td>
            </tr>
            <tr class="bg-gray-100">
              <td class="border px-4 py-2">DNS</td>
              <td class="border px-4 py-2">Amazon Route 53</td>
              <td class="border px-4 py-2">Google Cloud DNS</td>
              <td class="border px-4 py-2">Azure DNS</td>
            </tr>
            <tr>
              <td class="border px-4 py-2">Precio por consulta</td>
              <td class="border px-4 py-2">$0.40 por 1 millón de consultas</td>
              <td class="border px-4 py-2">$0.25 por 1 millón de consultas</td>
              <td class="border px-4 py-2">$0.50 por 1 millón de consultas</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
</script>

<style scoped></style>