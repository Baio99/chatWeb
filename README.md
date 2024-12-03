# Guía de Instalación del Proyecto

## Instalación del Backend

1. Clonar el repositorio del proyecto:

    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```

2. Abrir el proyecto en IntelliJ IDEA.

3. Asegúrate de tener instalado Gradle y el JDK de Amazon versión 17.

4. Crear la base de datos en PostgreSQL con el nombre especificado en el archivo `db.resource`.

5. Configura las credenciales de PostgreSQL (usuario y contraseña) en el archivo `db.resource`.

6. Ejecuta el backend:

    ```bash
    ./gradlew bootRun
    ```

   Al ejecutar el backend con el boton play de IntelliJ IDEA, se crearán automáticamente las tablas y la configuración de la base de datos.

---

## Instalación del Frontend

1. Instalar las dependencias del proyecto:

    ```bash
    npm install
    ```

2. Si no tienes Angular CLI instalado, instálalo globalmente:

    ```bash
    npm install -g @angular/cli
    ```

3. Para ejecutar el frontend de manera local, usa el siguiente comando:

    ```bash
    ng serve
    ```

4. Si deseas ejecutar el frontend con acceso desde cualquier red, usa el siguiente comando:

    ```bash
    ng serve --host 0.0.0.0
    ```

---

¡Con estos pasos deberías tener el backend y el frontend corriendo correctamente!
