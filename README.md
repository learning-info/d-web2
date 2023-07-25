# Prueba técnica: Creación de una API CRUD con NestJS y SQLite

En esta prueba, crearás una API que permita gestionar una lista de productos utilizando el framework NestJS y una base de datos SQLite. La API proporcionará operaciones CRUD (Crear, Leer, Actualizar y Eliminar) para administrar los elementos de la lista.

## Requerimientos:

1. **Configuración del Proyecto:** Crea un nuevo proyecto de NestJS utilizando el CLI de NestJS. Asegúrate de tener instalado Node.js y npm previamente.

2. **Base de Datos:** Configura la base de datos SQLite utilizando TypeORM en el archivo `app.module.ts`. Define una entidad llamada `Product` que represente los elementos de la lista con campos como `id`, `name`, `description` y `quantity`.

3. **Controlador y Servicio:** Crea un controlador llamado `AppController` que maneje las solicitudes HTTP para las operaciones CRUD. También crea un servicio llamado `AppService` que gestionará la lógica de negocio para el CRUD utilizando el repositorio de la entidad `Product`.

4. **Operaciones CRUD:**
   - **Crear (POST):** Agrega una nueva entrada a la lista de elementos con la información proporcionada en el cuerpo de la solicitud.

   - **Leer (GET):** Obtiene la lista completa de elementos existentes o recupera un elemento específico por su ID.

   - **Actualizar (PUT):** Actualiza la información de un elemento existente en la lista basándose en su ID y los datos proporcionados en el cuerpo de la solicitud.

   - **Eliminar (DELETE):** Elimina un elemento de la lista utilizando su ID.

5. **Pruebas:**
   - Utiliza herramientas como Postman o cURL para probar todas las operaciones CRUD de la API.

6. **Documentación: (Opcional)**
   - Documenta el proceso de instalación y ejecución del proyecto en este archivo `README.md`.

   - Describe cada una de las rutas de la API y los parámetros esperados en las solicitudes.

   - Incluye ejemplos de las solicitudes y respuestas para facilitar la comprensión y el uso de la API.

7. **Entrega:**
   - Sube el codigo a tu repositorio y que este el proyecto de forma pública, si el repositorio no se encuentra público directamente no se tomará en cuenta la prueba.

   - Sube el enlace de tu repositorio a la plataforma de la universidad (Campus).

8. **Bono (Opcional):**
   - Implementa validaciones de datos para asegurar que se envíen datos válidos en las solicitudes.

   - Añade autenticación y autorización a la API para proteger las operaciones CRUD.

Recuerda seguir las buenas prácticas de programación y mantener un código limpio y legible. No dudes en buscar información en la documentación oficial de NestJS, SQLite y TypeORM. ¡Buena suerte!
