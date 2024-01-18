# Proyecto de Blog con Flask

¡Bienvenido/a a mi proyecto de blog desarrollado con Flask!

Este proyecto es una aplicación web simple construida con Flask, que incluye características como registro de usuarios, inicio de sesión, creación y visualización de publicaciones en un blog.

## Características

- **Registro de Usuarios:** Los usuarios pueden registrarse proporcionando un correo electrónico, nombre y contraseña.

- **Inicio de Sesión:** Los usuarios registrados pueden iniciar sesión en la aplicación.

- **Creación de Publicaciones:** Los usuarios autenticados pueden crear nuevas publicaciones en el blog.

- **Visualización de Publicaciones:** Todas las publicaciones están disponibles para su visualización en la página principal.

- **Comentarios:** Los usuarios pueden dejar comentarios en las publicaciones.

## Instalación

1. Clona este repositorio: `git clone https://github.com/tu-usuario/tu-proyecto.git`
2. Crea un entorno virtual: `python -m venv venv`
3. Activa el entorno virtual:
   - En Windows: `venv\Scripts\activate`
   - En Linux/Mac: `source venv/bin/activate`
4. Instala las dependencias: `pip install -r requirements.txt`
5. Configura las variables de entorno en un archivo `.env` (puedes usar el archivo `.env.example` como referencia).

## Configuración

Asegúrate de configurar las variables de entorno necesarias para la aplicación, como la clave secreta (`SECRET_KEY`) y la URL de la base de datos (`DATABASE_URL`).

## Uso

Ejecuta la aplicación con el siguiente comando:

```bash
python app.py

Contribuciones
¡Las contribuciones son bienvenidas! Si encuentras algún problema o tienes sugerencias, por favor crea un problema o envía una solicitud de extracción.

Licencia
Este proyecto está bajo la Licencia MIT.

