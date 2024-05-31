 ---

# Proyecto Django: Blog de Autores y Etiquetas

Bienvenido a mi proyecto de Django, un blog que permite la gestión de posts, autores y etiquetas. Este proyecto está alojado en el siguiente enlace de Google Drive:

[Proyecto Django en Google Drive](https://drive.google.com/drive/folders/1eV7cGPL7_OmRWSp-bypXB_mI_FWn4xMd?usp=sharing)

## Descripción del Proyecto

Este proyecto es un blog que permite a los usuarios:
- Ver una lista de todos los posts
- Ver detalles de un post individual
- Filtrar posts por autor y por etiquetas
- Ver una lista de todos los autores y etiquetas

El proyecto está construido con Django y utiliza un modelo de datos sencillo para gestionar autores, etiquetas y posts.

## Estructura del Proyecto

- `models.py`: Define los modelos para autores, etiquetas y posts.
- `views.py`: Contiene las vistas para manejar las solicitudes HTTP y renderizar las plantillas.
- `urls.py`: Define las rutas de la aplicación.
- `templates/`: Contiene las plantillas HTML para renderizar las vistas.
- `static/`: Directorio para archivos estáticos como CSS y imagenes.

## Uso del Proyecto

- **Página Principal**: Muestra los 3 posts más recientes.
- **Lista de Posts**: `/posts/` - Muestra todos los posts ordenados por fecha.
- **Detalle de Post**: `/posts/<slug>` - Muestra detalles de un post específico.
- **Lista de Autores**: `/autors/` - Muestra todos los autores.
- **Detalle de Autor**: `/autors/<int:author_id>` - Muestra todos los posts de un autor específico.
- **Lista de Etiquetas**: `/tags/` - Muestra todas las etiquetas.
- **Posts por Etiqueta**: `/tags/<str:tag>` - Muestra todos los posts asociados a una etiqueta específica.

---
