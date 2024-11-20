<template>
  <div class="bg-white w-full min-h-screen p-10 flex flex-col">
    <h1 class="text-3xl font-bold">Fase de Diseño y Desarrollo</h1>

    <h2 class="text-xl font-bold mt-4 mx-8">
      Metodología de desarrollo
    </h2>
    <div class="w-full mx-auto m-8 flex flex-row">
      <div class="flex flex-col w-1/2 p-8">
        <section class="mb-8">
          <h2 class="text-2xl font-bold mb-4">SCRUM</h2>

          <p class="text-gray-700">
            SCRUM es un marco de trabajo ágil 
            que facilita la gestión y ejecución de proyectos complejos 
            mediante la colaboración, flexibilidad y entregas incrementales.
          </p>
        </section>

        <section class="mb-8">
          <h2 class="text-2xl font-bold mb-4">Roles</h2>
          <ul class="list-disc pl-6">
            <li class="text-gray-700">
              Product Owner (PO): Encargado de definir y priorizar los 
              requisitos del proyecto y velar por los intereses del cliente.
            </li>
            <li class="text-gray-700">
              Scrum Master: Facilitador de COREWEB que guía al equipo en la aplicación de Scrum y 
              asegura que se cumplan las prácticas ágiles.
            </li>
            <li class="text-gray-700">
              Equipo de Desarrollo: Compuesto por desarrolladores, diseñadores y otros profesionales 
              de COREWEB responsables de la implementación técnica.
            </li>
          </ul>
        </section>
      </div>
      <div class="flex flex-col w-1/2 p-8">
        <section class="mb-8">
          <h2 class="text-2xl font-bold mb-4">Proceso de Trabajo en Sprints</h2>
          <ul class="list-disc pl-6">
            <li class="text-gray-700">
              Sprint Planning: Antes de iniciar un sprint, se lleva a cabo una reunión para definir
               los objetivos y tareas a completar en un período de tiempo específico. Se eligen los 
               elementos del backlog que se pueden completar durante el sprint.
            </li>
            <li class="text-gray-700">
              Sprint: El equipo de desarrollo trabaja en las tareas asignadas, siguiendo un flujo 
              de trabajo iterativo. Se realizan reuniones diarias de 15 minutos para discutir avances,
               obstáculos y próximos pasos.
            </li>
            <li class="text-gray-700">
              Sprint Review: Al finalizar el sprint, se presenta el trabajo completado al Product 
              Owner para recibir feedback.
            </li>
          </ul>
        </section>
      </div>
    </div>
    <h2 class="text-xl font-bold mx-8">Herramientas</h2>
    <div class="flex flex-row justify-center gap-16">
      <div class="flex flex-col items-center">
        <h2 class="text-xl font-semibold mt-4">
          Herramientas para el desarrollo
        </h2>
        <div class="flex items-center ">
          <img
            src="../assets/images/desarrollo/s3.png"
            class="my-4 w-40 h-40 object-contain"
          />
          <img
            src="../assets/images/desarrollo/react.png"
            class="my-4 w-28 h-28 object-contain"
            />
            <img
              src="../assets/images/desarrollo/lambda.png"
              class="my-4 w-40 h-40 object-cover"
            />
        </div>
        <div class="flex gap-2">
            <img
              src="../assets/images/desarrollo/nodejs.png"
              class="my-4 w-52 object-contain"
            />
            <img
              src="../assets/images/desarrollo/mongo.jpg"
              class="my-4 w-36 object-contain"
            />
        </div>
      </div>
      <div class="flex flex-col items-center">
        <h2 class="text-xl font-semibold mt-4">
          Herramientas para el diseño 
        </h2>
        <img
          src="../assets/images/desarrollo/figma.png"
          alt="Aqui va una imagen chida :D"
          class="my-4 w-80 h-40 object-contain"
        />
        <img
          src="../assets/images/desarrollo/tailwind.png"
          alt="Aqui va una imagen chida :D"
          class="my-4 w-80 h-40 object-contain"
        />
      </div>
    </div>

    <h2 class="text-xl font-bold mt-4 mx-8">Diseño de las pantallas</h2>
    <h2 class="text-xl font-bold mt-4 mx-14">Vista de admin</h2>
    <div class="flex flex-row justify-center">
      <div class="flex flex-col items-center">
        <img
          src="../assets/images/desarrollo/expositor_desktop.png"
          alt="Aqui va una imagen chida :D"
          class="my-4 w-4/5"
        />
        <div class="text-gray-500">Vista Desktop</div>
      </div>
        <div class="flex flex-col items-center">
          <img
            src="../assets/images/desarrollo/expositor_mobile.png"
            class="my-4 w-4/5"
          />
          <div class="text-gray-500">Vista Mobile</div>
        </div>
    </div>


    <h2 class="text-xl font-bold mt-4 mx-14">Vista de usuarios</h2>
    <div class="flex flex-row justify-center">
      <div class="flex flex-col items-center">
        <img
          src="../assets/images/desarrollo/user_desktop.png"
          alt="Aqui va una imagen chida :D"
          class="my-4 w-4/5"
        />
        <div class="text-gray-500">Vista Desktop</div>
      </div>
        <div class="flex flex-col items-center">
          <img
            src="../assets/images/desarrollo/user_mobile.png"
            alt="Aqui va una imagen chida :D"
            class="my-4 w-4/5"
          />
          <div class="text-gray-500">Vista Mobile</div>
        </div>
    </div>
    
  </div>
</template>

<script lang="ts"></script>

<style scoped></style>
