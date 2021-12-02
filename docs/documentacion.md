# Documentación:

**IMPORTANTE LEER LA DOCUMENTACIÓN ANTES DE HACER COSAS PARA QUE TODO SE HAGA DE MANERA MODULAR**

## Creación de archivos:
La sintaxis de los archivos seguirá una lógica estándar para facilitar la manera de encontrar/editar los archivos creados.
- Las páginas tendrán la sub-extension 'es' o 'en' según el idioma al que corresponda.
  - Ej: inicio.es.html
  - Ej mal: inicioIngles.html
- Usar nombres cortos en minúsculas y snake_case:
  - Ej: Si la página es de inicio:
    - Bien: inicio.es.html
    - Mal: paginaDe_Inicio
- Los archivos se guardan en:
  - CSS van en la carpeta res/css.
  - img van en la carpeta res/img.
  
  - Crear una carpeta para archivos concretos de cada página.
  - Poner las que sean comunes a todas en global.  
  - Ej1: Si quiero poner el logo (logo.png), lo guardo en res/img/global
  - Ej1: Si quiero poner el archivo.css de página de solicitud de informacion, lo guardo en res/css/solicitud_informacion/