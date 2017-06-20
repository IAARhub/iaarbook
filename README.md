# Libro Online de la comunidad de Inteligencia Artificial Argentina

Repositorio con el material del [libro online de IAAR](https://iaarbook.github.io/).

## ¿Cómo contribuir?

Para poder generar el contenido del libro se necesita tener instalado [MkDocs](http://www.mkdocs.org/) y [Python](https://www.python.org/)

1. Clonar este repositorio
2. Crear un documento en [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) en la carpeta `docs` con el contenido que se quiere agregar
3. Modificar el archivo de configuración `mkdocs.yml` para agregar la referencia a la nueva página.
4. Desde la línea de comando, pararse en la carpeta principal `iaarbook` y ejecutar el comando `mkdocs build` para generar los archivos. Se va a generar todo el contenido del sitio estático en la carpeta `site`. 
5. Clonar el repositorio https://github.com/iaarbook/iaarbook.github.io.git
6. Copiar el contenido de la carpeta `site` reemplanzando el contenido del repositorio iaarbook.github.io
7. Pushear los cambios al repositorio iaarbook.github.io
8. Visitar [iaarbook.github.io](https://iaarbook.github.io) para ver los cambios.
