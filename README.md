# SICAP · Demo para GitHub Pages

Demo estática del Sistema Integral de Carga y Actualización de la Planificación Docente.

## Publicar en un repositorio nuevo

1. Creá un repositorio en GitHub.
2. Descomprimí este ZIP y subí todo su contenido directamente a la raíz del repositorio. Deben quedar `index.html`, `.nojekyll` y las carpetas/archivos de `assets/` en la raíz.
3. Confirmá los cambios en la rama `main`.
4. En **Settings → Pages**, elegí **Deploy from a branch**, rama `main`, carpeta `/(root)` y guardá.
5. GitHub mostrará la URL publicada en Settings → Pages. Para el usuario `siedfduncuyo-star`, el formato es `https://siedfduncuyo-star.github.io/NOMBRE-DEL-REPOSITORIO/`.

## Incluye

- Catálogo curricular aportado, datos de agenda disponibles y correlatividades del Plan 2017 del Anexo I de la Resolución 16/2021 CD.
- Turnos predeterminados: años 1.º y 2.º permiten mañana y tarde; desde 3.º, tarde.
- PDF para imprimir/guardar y documento Word editable.
- Montserrat y logo de la Facultad incluidos localmente.

## Padrón docente y privacidad

El informe de docentes contiene datos personales (nombres y correos) y no informa cargo ni título profesional. El padrón se mantiene como archivo CSV separado para importarlo desde la demo y **no está incluido en este repositorio**. Si el repositorio es público, no subas el CSV. Los cargos y títulos deben completarse en la interfaz.

## Alcance

GitHub Pages sirve esta demo en el navegador. Los borradores se guardan en el navegador local; no hay autenticación ni base de datos compartida. Para la aplicación central con usuarios y PostgreSQL se necesita desplegar la versión Django en un servidor.
