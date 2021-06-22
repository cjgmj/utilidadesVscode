# utilidadesVSCode

## Ediciones y tips básicos

- Abrir página con todos los atajos: `Ctrl + K Ctrl + R`.
- Copiar: `Ctrl + C`.
- Cortar: `Ctrl + X`.
- Pegar: `Ctrl + V`.
- Modo navegación: `Alt`.
- Desplazamiento entre palabras: `Ctrl + ← / →`.
- Mover línea o líneas seleccionada: `Alt + ↑ / ↓`.
- Comentar línea o líneas seleccionadas: `Ctrl + Ç`.
- Comentar código seleccionado o crear comentario en la posición del cursor: `Shift + Alt + A`.
- Crear archivo: en una ruta inexistente, `Ctrl + Click` y VSCode ofrecerá crear el archivo.
- Ir a la definición: sobre lo que queramos ver, `Ctrl + click` o `Ctrl + F12`.
- Ver definición sin salir del archivo: sobre lo que queramos ver, `F12`.
- Ver referencias sin salir del archivo: sobre lo que queramos ver, `Shift + F12`.
- Borrar línea o líneas seleccionadas: `Ctrl + Shift + K`.
- Seleccionar todas las coincidencias de un texto en el archivo: `Ctrl + Shift + L`.
- Deshacer cambios: `Ctrl + Z`.
- Rehacer cambios: `Ctrl + Shift + Z` o `Ctrl + Y`.
- Mostrar u ocultar barra lateral: `Ctrl + B`.
- Mostrar u ocultar panel inferior: `Ctrl + J`.
- Entrar en Zen mode: `Ctrl + K Z`.
- Salir del Zen mode: `F11`.
- Buscar archivos: `Ctrl + P`.
- Mostrar u ocultar terminal: `Ctrl + Ñ`.
- Crear nueva terminal: `Ctrl + Alt + O`.
- Dividir terminal: `Ctrl + Shift + 5`.
- Navegar entre terminales divididas: `Alt + ← / →`.
- Abrir paleta de comandos: `Ctrl + Shift + P` o `F1`.
- Envolver código: con código seleccionado, abrir la paleta de comandos y buscar `wrap with abbreviation` y escribir con lo que queramos envolver (acepta emmet).
- Abrir ventana shortcuts: `Ctrl + K Ctrl + S`.
- Cerrar pestaña: `Ctrl + W`.
- Cerrar todas las pestañas: `Ctrl + K Ctrl + W`.
- Cerrar carpeta: `Ctrl + K F`.
- Cerrar editor: `Ctrl + F4`.
- Reabrir pestaña anterior: `Ctrl + Shift + T`.
- Cambiar a la pestaña siguiente: `Ctrl + TAB`.
- Cambiar a la pestaña anterior: `Ctrl + Shift + TAB`.
- Crear nueva división: `Ctrl + número de divisiones + 1`.
- Navegar a división: `Ctrl + número de división`.
- Comprimir todos los bloques de código: `Ctrl + K Ctrl + 0`.
- Descomprimir todos los bloques de código: `Ctrl + K Ctrl + J`.
- Comprimir todos los bloques menos el actual: `Ctrl + K Ctrl + 1`.
- Comprimir bloques por nivel: `Ctrl + K Ctrl + 2-9`.
- Explorador: `Ctrl + Shift + E`.
- Búsqueda: `Ctrl + F`.
- Búsqueda en archivos: `Ctrl + Shift + F`.
- Reemplazar: `Ctrl + H`.
- Reemplazar en archivo: `Ctrl + Shift + H`.
- Control versiones: `Ctrl + Shift + G G`.
- Run: `Ctrl + Shift + D`.
- Crear nuevo archivo: `Ctrl + N`.
- Crear nueva ventana: `Ctrl + Shift + N`.
- Abrir archivo: `Ctrl + O`.
- Abrir carpeta: `Ctrl + K Ctrl + O`.

## Multi cursores y edición rápida

- Clonar líneas: `Shift + Alt + ↑ / ↓`.
- Multi cursor básico: `Ctrl + Shift + Alt + ↑ / ↓`.
- Multi cursor en un punto concreto: `Alt + Click`.
- Seleccionar todo: `Ctrl + A`.
- Seleccionar palabras: `Ctrl + Shift + ← / →`.
- Seleccionar palabra completa sin importar posición del cursor: `Shift + Alt + ← / →`.
- Seleccionar línea completa con salto de línea: `Ctrl + L`.
- Seleccionar fila desde el principio: `Shift + Fin`.
- Seleccionar fila desde el final: `Shift + Inicio`.
- Seleccionar desde el cursor hasta el principio del documento: `Ctrl + Shift + Inicio`.
- Seleccionar desde el cursor hasta el final del documento: `Ctrl + Shift + Fin`.
- Lowercase: `Ctrl + Alt + X`.
- Uppercase: `Ctrl + Shift + X`.
- Siguiente ocurrencia seleccionándola junto a las anteriores desde la primera seleccionada: `Ctrl + D`.
- Mover cursor a la siguiente ocurrencia: `Ctrl + F3`.
- Mover cursor a la anterior ocurrencia: `Ctrl + Shift + F3`.

## Definiciones y Snippets

- Ver definicion: `Ctrl + P @` o `Ctrl + Shift + O`.
- Ver definiciones agrupadas: `Ctrl + P @:` o `Ctrl + Shift + O :`.
- Ir a una línea: `Ctrl + P :` o `Ctrl + G`.
- Preview Markdown: `Ctrl + Shift + P` o `F1` y poner `Markdown Open Preview` o `Markdown Open Preview to the side`, este último permite ver los cambios en tiempo real.
- Reemplazar símbolo: para cambiarlo de forma local, con lo que queramos cambiar seleccionado, pulsamos `F2`. Para cambiarlo de forma global, hacerlo en el archivo principal.
- Crear snippets: `Ctrl + Shift + P`, poner `Configure User Snippets` y elegir el lenguaje para el que queramos crear el snippet. El snippet está compuesto por varias partes:
  - Nombre del snippet.
  - `prefix`: cadena con el que se mostrará el snippet.
  - `body`: el código que será introducido. Se pueden meter variables con `$` más un índice. Se le puede dar valores por defecto a las variables con `${índice:valor}`. Una vez introducido el snippet se podrá navegar entre las variables con `TAB` en el orden que se le haya puesto. Si no tiene variables, el cursor se pondrá al final del código introducido.
  - `descripction`: es opcional, sirve para indicar la funcionalidad del snippet.

## Extensiones

- TODO Tree: Añadir en los ajustes `**/node_modules/**` en `Exclude Globs`.

  ```json
  "todo-tree.highlights.customHighlight": {
    "TODO": {
      "icon": "check",
      "type": "line",
      "foreground": "#0D6EFF",
      "background": "#031B40",
      "iconColour": "#0D6EFF",
      "gutterIcon": true
    },
    "FIXME": {
      "icon": "tools",
      "type": "line",
      "foreground": "#FFDB0D",
      "background": "#403703",
      "iconColour": "#FFDB0D",
      "gutterIcon": true
    },
    "BUG": {
      "icon": "alert",
      "type": "line",
      "foreground": "#FF0000",
      "background": "#400000",
      "iconColour": "#FF0000",
      "gutterIcon": true
    }
  }
  ```

- Bookmarks: Podemos añadir o quitar una marca con `Ctrl + Alt + K`.
- Color Highlight: poner en `Marker Type` el valor `dot-before`, dentro de los ajustes.
- Bracket Pair Colorizer 2: añadir en los ajustes la siguiente configuración.

  ```json
  "bracket-pair-colorizer-2.colors": [
      "#d4d4d4",
      "#358cd6",
      "#8cdcfe",
      "#dcdc8b",
      "#4bbda6",
      "#c586c0"
  ]
  ```
