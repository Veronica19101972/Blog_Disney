# Blog_Disney

Trabajo Final de Python

A continuación, proporciono una guía general para llevar a cabo este proyecto.

1. Configuración del entorno:
   - Instala Python en tu sistema si aún no lo tienes.
   - Instala Django utilizando el administrador de paquetes de Python (pip).
   - Crea un nuevo proyecto de Django utilizando el comando `django-admin startproject project`.
   - Crea una nueva aplicación dentro del proyecto con el comando `python manage.py startapp home`.

2. Diseño de la base de datos:
   - Define los modelos necesarios para tu aplicación. Por ejemplo, puedes tener un modelo `User` para los usuarios registrados, un modelo `Blog` para los blogs y un modelo `Page` para las páginas.
   - Configura las relaciones entre los modelos, como una relación de muchos a uno entre los blogs y los usuarios.

3. Creación de vistas y plantillas:
   - Crea vistas en Django que manejen las solicitudes para las diferentes páginas y funcionalidades de tu aplicación.
   - Crea plantillas HTML que muestren la información y los formularios correspondientes a cada vista.

4. Implementación de la funcionalidad de registro y autenticación:
   - Crea las vistas y formularios necesarios para el registro de usuarios.
   - Implementa la funcionalidad de inicio de sesión utilizando Django's built-in authentication views.
   - Asegúrate de proteger las rutas que solo deben ser accesibles para los usuarios registrados o administradores.

5. Creación de la funcionalidad de perfiles:
   - Crea una vista de perfil que muestre la información del usuario y permita realizar modificaciones.
   - Implementa la lógica para actualizar la información del perfil y eliminar la cuenta del usuario.

6. Implementación de las páginas de blogs:
   - Crea una vista que muestre una lista de todos los blogs en el route `pages/`.
   - Crea una vista que muestre los detalles de un blog específico al hacer clic en "Leer más" en la lista de blogs.
   - Asegúrate de manejar el caso en el que no haya páginas disponibles y mostrar un mensaje adecuado.

7. Gestión de imágenes y archivos estáticos:
   - Configura la carga y almacenamiento de imágenes utilizando Django's FileField o ImageField en el modelo `Blog`.
   - Asegúrate de configurar correctamente la ruta de carga y servir los archivos estáticos en tu proyecto de Django.

8. Implementación del panel de administración:
   - Registra tus modelos en el archivo `admin.py` de tu aplicación para habilitar la interfaz de administración de Django.
   - Personaliza el panel de administración según tus necesidades.

9. Pruebas y documentación:
   - Crea casos de prueba para verificar el funcionamiento correcto de tu aplicación.
   - Documenta tus casos de prueba en una carpeta en tu repositorio de GitHub.
   - Asegúrate de tener un archivo README.md en tu repositorio que incluya los nombres completos de los participantes y una breve descripción de las contribuciones de cada uno.

