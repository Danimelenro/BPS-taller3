**Veterinaria Django App**

Este repositorio contiene una aplicación Django diseñada para gestionar información relacionada con mascotas en una clínica veterinaria. A continuación, se proporciona una breve descripción de los archivos y su funcionalidad:

### Archivos Principales:

1. **`models.py`**: Define el modelo de datos para la aplicación, incluyendo la clase `Mascota` con campos como nombre, especie, raza, edad y propietario.

2. **`urls.py`**: Configura las rutas URL de la aplicación, vinculando diferentes vistas a patrones de URL. Incluye una ruta para la interfaz de administración y otra para acceder a las vistas de la aplicación 'Mascotas Felices'.

3. **`settings.py`**: Contiene la configuración principal de la aplicación, incluyendo la conexión a la base de datos MySQL y otras configuraciones importantes de Django.

4. **`views.py`**: Contiene las vistas de la aplicación, como la vista `lista_mascotas` que recupera todas las mascotas de la base de datos y las muestra en una plantilla.

5. **`manage.py`**: El script de gestión principal de Django, utilizado para ejecutar tareas administrativas desde la línea de comandos.

### Carpetas:

1. **`Mascotas Felices/`**: Carpeta de la aplicación principal que puede contener archivos como `urls.py` específicos de la aplicación, plantillas HTML y otros componentes relacionados con la lógica de la aplicación.

### Instrucciones de Ejecución:

1. Asegúrate de tener Django instalado en tu entorno de desarrollo.

2. Configura la base de datos en `settings.py` con la información correcta, incluyendo el nombre de la base de datos, usuario y contraseña.

3. Ejecuta `python manage.py migrate` para aplicar las migraciones y crear las tablas en la base de datos.

4. Inicia el servidor de desarrollo con `python manage.py runserver`.

5. Accede a la aplicación a través de tu navegador web en la URL proporcionada por el servidor de desarrollo.

Este es un esquema básico para comenzar con la aplicación. Puedes personalizar y expandir la funcionalidad según tus necesidades. ¡Diviértete programando con Django!
