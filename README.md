# Preguntados XIV

Juego de preguntas por equipos para la XIV. Categorías: Infancia, Ruca (FASTA), Deporte y Cultura general.

- De 2 a 8 equipos con nombres propios.
- Ruleta manual con cinco casillas, incluida Corona, frenado progresivo y presentación de categoría antes de comenzar.
- Selección de categoría para coronas al obtener tres aciertos o caer en Corona.
- Banco separado de preguntas difíciles para coronas.
- Temporizador configurable desde Preguntas, con tiempos separados para turno y corona. El reloj empieza al pulsar Comenzar. Comodines por equipo: llamada, 50/50 y tiempo extra.
- Editor con cuatro opciones por pregunta, respuesta correcta, imágenes y audios.
- Guardado en IndexedDB del navegador y respaldos JSON.

## GitHub Pages

Publicar desde la rama `main`, carpeta raíz `/`, en Settings → Pages.

Este proyecto no necesita instalación ni compilación. `index.html`, `style.css` y `app.js` contienen la aplicación completa.

## Pasar datos desde Sites

En la versión de Sites, abrir Preguntas → Descargar respaldo. En GitHub Pages, abrir Preguntas → Importar respaldo y elegir ese archivo. Esto traslada preguntas y adjuntos; la partida comienza de nuevo. Cada dominio guarda sus datos por separado.

## Edición

Las preguntas cargadas desde el juego se guardan en ese navegador, no en el repositorio. Para cambiar el banco inicial o la aplicación, editar `app.js` y subir los cambios a `main`.
