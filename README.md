# SICAP · Demo funcional

Demo estática para GitHub Pages del Sistema Integral de Carga y Actualización de la Planificación Docente.

## Publicar en un repositorio nuevo

1. Creá un repositorio en GitHub, por ejemplo `SICAP-demo`.
2. Descomprimí el paquete y subí **todo el contenido de esta carpeta** a la raíz del repositorio. Deben quedar `index.html` y `assets/` directamente en la raíz.
3. Confirmá los cambios en la rama `main`.
4. En **Settings → Pages**, elegí **Deploy from a branch**, rama `main`, carpeta `/(root)` y guardá.
5. Esperá la publicación. Para un repositorio llamado `SICAP-demo`, la dirección será `https://siedfduncuyo-star.github.io/SICAP-demo/`. GitHub muestra la dirección exacta en Settings → Pages.

## Alcance de esta demo

La demo funciona en el navegador: contiene el catálogo y la agenda incluidos, permite completar el asistente, guardar borradores localmente, editar unidades y descargar PDF mediante impresión o Word editable. No usa autenticación ni base de datos central. Los borradores se guardan solo en el navegador que los carga.

El padrón de docentes con correos no está dentro del repositorio. Para probarlo, se importa el CSV privado desde el control de la demo; no subas ese archivo a un repositorio público. El informe fuente no incluye cargos docentes, por eso deben confirmarse.
