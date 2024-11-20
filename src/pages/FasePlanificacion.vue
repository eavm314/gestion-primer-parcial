<template>
    <div class="p-4 bg-white">
        <h1 class="text-3xl font-bold text-center text-gray-800 mb-8">Cronograma de Actividades</h1>
        <!-- Fase de Inicio -->
        <div class="bg-white rounded-lg shadow-md p-6">
            <h2 class="text-2xl font-semibold text-gray-700">1. Fase de Inicio</h2>
            <div class="mt-4 grid grid-cols-2 gap-4">
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">a. Reunión con el cliente para definir requisitos y objetivos</h3>
                    <p class="text-gray-600">Duración: Día 1 - 2</p>
                    <p class="text-gray-600">Herramientas: Google Docs, Sheets</p>
                    <p class="text-gray-600">Responsable: Gerente de Proyecto</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">b. Creación del documento de inicio de proyecto</h3>
                    <p class="text-gray-600">Duración: Día 3 - 8</p>
                    <p class="text-gray-600">Herramientas: Google Docs</p>
                    <p class="text-gray-600">Responsable: Gerente de Proyecto</p>
                </div>
            </div>
        </div>

        <!-- Fase de Planificación -->
        <div class="bg-white rounded-lg shadow-md p-6 mt-6">
            <h2 class="text-2xl font-semibold text-gray-700">2. Fase de Planificación</h2>
            <div class="mt-4 grid grid-cols-2 gap-4">
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">a. Elaboración del Plan de Trabajo para el desarrollo de la página</h3>
                    <p class="text-gray-600">Duración: Día 9 - 14</p>
                    <p class="text-gray-600">Herramientas: Trello, Notion</p>
                    <p class="text-gray-600">Responsables: Gerente de Proyecto, Líder técnico</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">b. Reunión inicial con todo el equipo (Sprint Planning)</h3>
                    <p class="text-gray-600">Fecha: Día 15</p>
                    <p class="text-gray-600">Herramientas: Google Meet, Trello</p>
                    <p class="text-gray-600">Responsable: Líder técnico</p>
                </div>
            </div>
        </div>

        <!-- Fase de Diseño -->
        <div class="bg-white rounded-lg shadow-md p-6 mt-6">
            <h2 class="text-2xl font-semibold text-gray-700">3. Fase de Diseño</h2>
            <div class="mt-4 grid grid-cols-2 gap-4">
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">a. Diseño de la interfaz de usuario y navegación del usuario (Mockups)</h3>
                    <p class="text-gray-600">Duración: Día 15 - 22</p>
                    <p class="text-gray-600">Herramientas: Figma</p>
                    <p class="text-gray-600">Responsable: Diseñador UI/UX</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">b. Presentación de la propuesta de diseño</h3>
                    <p class="text-gray-600">Fecha: Día 23</p>
                    <p class="text-gray-600">Herramientas: Google Meet</p>
                    <p class="text-gray-600">Responsables: Gerente de Proyecto, Diseñador UI/UX</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">c. Ajustes al diseño de acuerdo a observaciones del cliente (si aplica)</h3>
                    <p class="text-gray-600">Duración: Día 23 - 24</p>
                </div>
            </div>
        </div>

        <!-- Fase de Desarrollo -->
        <div class="bg-white rounded-lg shadow-md p-6 mt-6">
            <h2 class="text-2xl font-semibold text-gray-700">4. Fase de Desarrollo</h2>
            <div class="mt-4 grid grid-cols-2 gap-4">
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">a. Arquitectura y estructura del sitio web</h3>
                    <p class="text-gray-600">Duración: Día 24 - 30</p>
                    <p class="text-gray-600">Herramientas: Draw.io, Figma</p>
                    <p class="text-gray-600">Responsables: Desarrolladores Frontend y Backend</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">b. Implementación de funcionalidades interactivas en el sitio web</h3>
                    <p class="text-gray-600">Duración: Día 31 - 55</p>
                    <p class="text-gray-600">Herramientas: Github, Trello, Notion</p>
                    <p class="text-gray-600">Responsables: Desarrollador Frontend, Fullstack</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">c. Implementación de lógica del lado del servidor</h3>
                    <p class="text-gray-600">Duración: Día 45 - Día 65</p>
                    <p class="text-gray-600">Herramientas: Github, Trello, Notion</p>
                    <p class="text-gray-600">Responsables: Desarrollador Backend, Fullstack</p>
                </div>
            </div>
        </div>

        <!-- Fase de Implementación -->
        <div class="bg-white rounded-lg shadow-md p-6 mt-6">
            <h2 class="text-2xl font-semibold text-gray-700">6. Fase de Implementación</h2>
            <div class="mt-4 grid grid-cols-2 gap-4">
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">a. Optimización SEO del sitio para buscadores web</h3>
                    <p class="text-gray-600">Duración: Día 79 - 80</p>
                    <p class="text-gray-600">Herramientas: Google Search Tools</p>
                    <p class="text-gray-600">Responsables: Desarrollador Frontend</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">b. Despliegue del sitio en el servidor seleccionado</h3>
                    <p class="text-gray-600">Duración: Día 81 - 83</p>
                    <p class="text-gray-600">Herramientas: AWS</p>
                    <p class="text-gray-600">Responsable: Ingeniero DevOps</p>
                </div>
            </div>
        </div>

        <!-- Fase de Cierre -->
        <div class="bg-white rounded-lg shadow-md p-6 mt-6">
            <h2 class="text-2xl font-semibold text-gray-700">7. Fase de Cierre</h2>
            <div class="mt-4 grid grid-cols-2 gap-4">
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">a. Tutoriales para la gestión de contenido y funcionalidades del sitio web</h3>
                    <p class="text-gray-600">Duración: Día 84 - 86</p>
                    <p class="text-gray-600">Herramientas: Google Docs</p>
                    <p class="text-gray-600">Responsable: Líder técnico</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">b. Elaboración de manual de usuario para navegación por el sitio web</h3>
                    <p class="text-gray-600">Duración: Día 86 - 88</p>
                    <p class="text-gray-600">Herramientas: Google Docs</p>
                    <p class="text-gray-600">Responsables: Desarrollador Frontend, Líder técnico</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">c. Preparación para la presentación y demostración del producto</h3>
                    <p class="text-gray-600">Duración: Día 88 - 90</p>
                    <p class="text-gray-600">Herramientas: Google Meet, Google Slides</p>
                    <p class="text-gray-600">Responsables: Gerente de Proyecto, Líder técnico</p>
                </div>
                <div class="border-2 border-gray-600 p-2">
                    <h3 class="text-lg font-semibold text-gray-800">d. Presentación final y entrega formal al equipo de EXPOHOGAR</h3>
                    <p class="text-gray-600">Fecha: Día 90</p>
                    <p class="text-gray-600">Herramientas: Google Meet, Google Slides</p>
                    <p class="text-gray-600">Responsables: Gerente de Proyecto, Líder técnico</p>
                </div>
            </div>
        </div>
    </div>
    
    <div class="m-8">
        <h3 class="text-xl font-semibold">Herramientas</h3>
        <div class="flex">
            <img class="m-auto w-80" src="../assets/images/plan/trello.png" alt="trello-board">
            <img class="m-auto w-60" src="../assets/images/plan/herramientas_google.jpeg" alt="google">
            <img class="m-auto w-80" src="../assets/images/plan/notion.png" alt="notion">

        </div>
    </div>
    <h3 class="text-xl ml-8 font-semibold">Trello Board</h3>
    <img class="m-auto" src="../assets/images/plan/trello-board.png" alt="trello-board">

    <h1 class="text-3xl font-bold text-center text-gray-800 my-8">Gestión de Riesgos</h1>

     <!-- Evaluación de Riesgos -->
     <div class="m-8">
        <h3 class="text-xl font-semibold text-gray-800">Evaluación de Riesgos</h3>
        <div class="mt-4 grid grid-cols-2 gap-4">
            <!-- Riesgo 1 -->
            <div class="border-2 border-gray-600 p-2">
                <h4 class="text-lg font-semibold text-gray-800">Riesgo 1: Cambios en los Requisitos del Cliente</h4>
                <p class="text-gray-600"><strong>Probabilidad:</strong> Moderada</p>
                <p class="text-gray-600"><strong>Impacto:</strong> Alto</p>
                <p class="text-gray-600"><strong>Descripción:</strong> Existe la posibilidad de que el cliente solicite modificaciones significativas en los requisitos del sitio web durante el desarrollo, lo que podría afectar tanto el alcance como los plazos establecidos del proyecto.</p>
            </div>
            <!-- Riesgo 2 -->
            <div class="border-2 border-gray-600 p-2">
                <h4 class="text-lg font-semibold text-gray-800">Riesgo 2: Retrasos en la Entrega de Contenido por parte de EXPOHOGAR</h4>
                <p class="text-gray-600"><strong>Probabilidad:</strong> Alta</p>
                <p class="text-gray-600"><strong>Impacto:</strong> Moderado</p>
                <p class="text-gray-600"><strong>Descripción:</strong> La entrega oportuna de contenido (textos, imágenes, videos, etc.) es esencial para cumplir con el cronograma. Los retrasos por parte de EXPOHOGAR podrían impactar la línea de tiempo del proyecto.</p>
            </div>
            <!-- Riesgo 3 -->
            <div class="border-2 border-gray-600 p-2">
                <h4 class="text-lg font-semibold text-gray-800">Riesgo 3: Problemas Técnicos con la Infraestructura de AWS</h4>
                <p class="text-gray-600"><strong>Probabilidad:</strong> Baja</p>
                <p class="text-gray-600"><strong>Impacto:</strong> Alto</p>
                <p class="text-gray-600"><strong>Descripción:</strong> Dependemos de la infraestructura de AWS para el hosting del sitio web. Problemas como interrupciones en el servicio o configuraciones incorrectas podrían impactar negativamente el desempeño del sistema.</p>
            </div>
            <!-- Riesgo 4 -->
            <div class="border-2 border-gray-600 p-2">
                <h4 class="text-lg font-semibold text-gray-800">Riesgo 4: Problemas de Seguridad del Sitio Web</h4>
                <p class="text-gray-600"><strong>Probabilidad:</strong> Moderada</p>
                <p class="text-gray-600"><strong>Impacto:</strong> Alto</p>
                <p class="text-gray-600"><strong>Descripción:</strong> Dado que el sitio web manejará información sensible (registros de usuarios, inscripciones), existe el riesgo de ataques cibernéticos o vulnerabilidades que comprometan la integridad del sistema y los datos de los usuarios.</p>
            </div>
            <!-- Riesgo 5 -->
            <div class="border-2 border-gray-600 p-2">
                <h4 class="text-lg font-semibold text-gray-800">Riesgo 5: Falta de Alineación en la Comunicación con el Cliente</h4>
                <p class="text-gray-600"><strong>Probabilidad:</strong> Moderada</p>
                <p class="text-gray-600"><strong>Impacto:</strong> Moderado</p>
                <p class="text-gray-600"><strong>Descripción:</strong> La falta de claridad o coordinación en la comunicación podría generar malentendidos respecto al alcance y las expectativas del proyecto.</p>
            </div>
        </div>
    </div>

    
    <!-- Estrategias de Mitigación -->
    <!-- <h2 class="text-2xl ml-8 font-semibold text-gray-700">Plan de Gestión de Riesgos</h2> -->
    <div class="m-8">
        <h3 class="text-xl font-semibold text-gray-800">Estrategias de Mitigación</h3>
        <div class="mt-4 grid grid-cols-1 md:grid-cols-2 gap-4">
            <!-- Estrategia: Cambios en los Requisitos del Cliente -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Cambios en los Requisitos del Cliente</h4>
                <ul class="list-disc list-inside text-gray-600 mt-2">
                    <li>Mantener una comunicación continua con EXPOHOGAR y realizar reuniones regulares para alinear expectativas.</li>
                    <li>Incorporar revisiones y aprobaciones formales en cada etapa del desarrollo.</li>
                </ul>
            </div>
            <!-- Estrategia: Retrasos en la Entrega de Contenido -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Retrasos en la Entrega de Contenido</h4>
                <ul class="list-disc list-inside text-gray-600 mt-2">
                    <li>Establecer un cronograma claro para la entrega de contenido, incluyendo recordatorios regulares al cliente.</li>
                    <li>Incluir márgenes de tiempo en el plan para acomodar posibles retrasos.</li>
                </ul>
            </div>
            <!-- Estrategia: Problemas Técnicos con la Infraestructura de AWS -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Problemas Técnicos con la Infraestructura de AWS</h4>
                <ul class="list-disc list-inside text-gray-600 mt-2">
                    <li>Realizar configuraciones iniciales de AWS siguiendo las mejores prácticas recomendadas.</li>
                    <li>Monitorear activamente el rendimiento y la disponibilidad de los servicios durante el desarrollo y pruebas.</li>
                </ul>
            </div>
            <!-- Estrategia: Problemas de Seguridad del Sitio Web -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Problemas de Seguridad del Sitio Web</h4>
                <ul class="list-disc list-inside text-gray-600 mt-2">
                    <li>Implementar prácticas de desarrollo seguro (validación de entradas, cifrado de datos).</li>
                </ul>
            </div>
            <!-- Estrategia: Falta de Alineación en la Comunicación con el Cliente -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Falta de Alineación en la Comunicación con el Cliente</h4>
                <ul class="list-disc list-inside text-gray-600 mt-2">
                    <li>Utilizar herramientas de gestión de proyectos (Jira, Trello) para documentar y rastrear los avances y cambios.</li>
                    <li>Designar un punto de contacto principal para centralizar la comunicación.</li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Plan de Contingencia -->
    <div class="m-8">
        <h3 class="text-xl font-semibold text-gray-800">Plan de Contingencia</h3>
        <div class="mt-4 grid grid-cols-1 md:grid-cols-2 gap-4">
            <!-- Contingencia: Cambios en los Requisitos del Cliente -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Cambios en los Requisitos del Cliente</h4>
                <p class="text-gray-600 mt-2">Incorporar tiempo y recursos adicionales al cronograma en caso de cambios inevitables. Proponer un costo adicional para cubrir los cambios significativos fuera del alcance inicial.</p>
            </div>
            <!-- Contingencia: Retrasos en la Entrega de Contenido -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Retrasos en la Entrega de Contenido</h4>
                <p class="text-gray-600 mt-2">Contratar servicios temporales de creación de contenido o buscar alternativas para avanzar en otras áreas del proyecto mientras se recibe el contenido pendiente.</p>
            </div>
            <!-- Contingencia: Problemas Técnicos con la Infraestructura de AWS -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Problemas Técnicos con la Infraestructura de AWS</h4>
                <p class="text-gray-600 mt-2">Configurar un entorno de prueba local para continuar el desarrollo en caso de interrupciones en AWS. Tener configurados planes de recuperación y respaldo.</p>
            </div>
            <!-- Contingencia: Problemas de Seguridad del Sitio Web -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Problemas de Seguridad del Sitio Web</h4>
                <p class="text-gray-600 mt-2">Establecer un plan de respuesta a incidentes de seguridad, incluyendo procedimientos para restaurar sistemas.</p>
            </div>
            <!-- Contingencia: Falta de Alineación en la Comunicación con el Cliente -->
            <div class="border-2 border-gray-600 p-4">
                <h4 class="text-lg font-semibold text-gray-800">Falta de Alineación en la Comunicación con el Cliente</h4>
                <p class="text-gray-600 mt-2">Programar reuniones adicionales para clarificar objetivos y resolver malentendidos rápidamente. Escalar problemas críticos al nivel directivo si es necesario.</p>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">
</script>

<style></style>
