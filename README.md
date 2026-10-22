# SICAP · Demo para GitHub Pages

Demo estática del Sistema Integral de Carga y Actualización de la Planificación Docente.

## Publicar en un repositorio nuevo

1. Creá un repositorio en GitHub.
2. Descomprimí este ZIP y subí todo su contenido directamente a la raíz del repositorio. Deben quedar `index.html`, `.nojekyll` y `assets/` en la raíz.
3. Confirmá los cambios en la rama `main`.
4. En **Settings → Pages**, elegí **Deploy from a branch**, rama `main`, carpeta `/(root)` y guardá.
5. GitHub mostrará la URL publicada en Settings → Pages.

## Datos y comportamiento

- El listado curricular precarga carga horaria total y carácter obligatorio/optativo según la tabla compartida.
- El régimen es semestral y queda fijo.
- En 1.º y 2.º año se puede elegir turno mañana o tarde; desde 3.º, el turno queda fijado en tarde.
- Las correlatividades muestran nombre y número de cada espacio, con los criterios de cursado/rendición de la resolución aportada.
- La agenda y la carga semanal se precargan desde los días y horarios del cronograma compartido, según el turno elegido. Donde la agenda no aporta un registro, la carga semanal queda vacía y el recuadro de agenda no aparece.
- Incluye PDF imprimible, Word editable, Montserrat y logo local.

## Padrón docente y privacidad

El informe de docentes contiene nombres y correos, pero no informa cargo ni título profesional. El CSV se importa desde la interfaz y no está incluido en este repositorio. No lo subas a un repositorio público.

## Alcance

GitHub Pages sirve la demo en el navegador. Los borradores se guardan localmente; no hay autenticación ni base de datos compartida.
