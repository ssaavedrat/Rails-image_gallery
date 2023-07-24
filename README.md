# Galería de Imágenes Interactivas - Desafío en Ruby on Rails

Este es un proyecto que consiste en crear una galería de imágenes interactivas utilizando una plantilla HTML, CSS y JavaScript. El objetivo es integrar la plantilla en Ruby on Rails y agregar una nueva vista que muestre información sobre la galería.

## Requisitos

1. Descargar e integrar la plantilla HTML de la aplicación. La plantilla deberá estar en una ruta index, que será la ruta raíz de la aplicación.

2. Los archivos CSS y JS de la plantilla deben ser incorporados en los respectivos directorios de assets de Rails.

3. La integración de los archivos CSS y JS se realizará desde el archivo `application.html.erb`.

4. Implementar un controlador llamado "Pages" que retorne una vista que muestre información acerca de en qué consiste la galería.

5. La información sobre la galería deberá estar como un elemento de tipo ancla que permita redirigir a los usuarios a dicha vista.

## Instalación

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

1. Clona el repositorio en tu máquina local:

    ```bash
    git clone https://github.com/tu-usuario/image_gallery.git
    ```

2. Ingresa al directorio del proyecto:

    ```bash
    cd image_gallery
    ```

3. Instala las gemas requeridas:

    ```bash
    bundle install
    ```

4. Inicia el servidor de desarrollo de Rails:

    ```bash
    rails server
    ```

El proyecto ahora estará disponible en tu navegador en `http://localhost:3000`.

## Estructura del Proyecto

El proyecto tiene la siguiente estructura básica:

```bash
image_gallery/
  ├── app/
  │   ├── assets/
  │   │   ├── images/
  │   │   ├── javascripts/
  │   │   └── stylesheets/
  │   ├── controllers/
  │   │   └── pages_controller.rb
  │   ├── views/
  │   │   ├── pages/
  │   │   │   ├── index.html.erb
  │   │   │   └── description.html.erb
  │   │   └── layouts/
  │   │       └── application.html.erb
  │   └── ...
  ├── config/
  │   ├── routes.rb
  │   └── ...
  ├── ...
  └── ...
```

## Contribuciones

Este es un proyecto de desafío, por lo que actualmente no aceptamos contribuciones externas. Si tienes preguntas o sugerencias, por favor crea un "Issue" en el repositorio.

## Créditos

La plantilla utilizada en este proyecto es proporcionada por [Nombre del Proveedor de la Plantilla] y está disponible en el siguiente enlace: [Enlace a la plantilla].
