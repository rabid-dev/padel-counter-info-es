# Sonidos Extra

![CustomSounds](../assets/customsounds.png "CustomSounds"){: style="display:block;margin-left:auto;margin-right:auto;width:60%;padding-top:10px;padding-bottom:10px;"}

En esta pantalla puedes añadir/editar/quitar sonidos extra que se reproducirán durante los partidos.

Los sonidos extra son sonidos cortos que se reproducirán en diferentes circunstancias, añadiendo un poco de chispa y risas a la partida.

Para usarlos recuerda que tienes que activar la opción [Activar Sonidos Extra](./general.md#activar-sonidos-extra) en la pestaña de [Ajustes Generales](./general.md).

También puedes añadir algunos sonidos de ejemplo usando el botón `Añadir ejemplos`

## Categorías de Sonidos Extra

A día de hoy los sonidos extra se reproducirán en las siguientes circunstancias.

- Al puntuar.
- Al ganar un juego.
- Al ganar un juego perfecto, esto significa ganar por 40-0.
- Al ganar un juego rápidamente, esto significa ganar por 40-0 y en un corto periodo de tiempo.
- Al hacer un punto de remontada. Una remontada sucede cuando un equipo va ganando por 40-0 pero luego el otro equipo va puntuando hasta llegar a 40-40 y está a 1 punto de ganar el juego.
- Al ganar un juego por remontada. Después de hacer un punto de remontada, si finalmente el equipo que iba perdiendo gana, se producirá este evento.
- Al ganar un set.
- Al ganar el partido.

## Añadir Sonidos Extra

Para añadir sonidos extra haz clic en el botón `Añadir Sonidos`. Si no le diste permisos de almacenamiento a la app, se te solicitará hacerlo.

Aquí puedes elegir entre:

- Un único fichero `.ogg`
- Una carpeta que contenga varios ficheros `.ogg`

!!! note
    A día de hoy la app solo soporta ficheros `.ogg`, pero intentaré mejorar esto en el futuro.

![Files](../assets/files.png "Files"){: style="display:block;margin-left:auto;margin-right:auto;width:60%;padding-top:10px;padding-bottom:10px;"}

Estos archivos se añadirán a la categoría que estaba seleccionada en el desplegable central.

!!! warning
    Ten en cuenta de que los sonidos tienen que ocupar menos de **1 Megabyte** y durar menos de **10 segundos.**

    También mencionar que los sonidos de **puntuación** durarán solo **2 segundos** y el resto durarán **5 segundos**. Al resto del sonido se le aplicará un efecto de desvanecimiento (fade out).

    Esto se hace para evitar que los sonidos tarden mucho en reproducirse del todo y agilizar el partido.

### Añadir sonidos extra de forma rápida

Hay una forma más rápida de añadir muchos sonidos con solo 1 carpeta: creando una estructura de carpetas ya categorizada.

Para ello, crea una carpeta con la siguiente estructura (como ejemplo nuestra carpeta se llamará `MisSonidosExtra`)

```bash
/MisSonidosExtra
├── comeback_game
├── comeback_scoring
├── quick_game
├── scoring
├── win_game
├── win_game_40_0
├── win_match
└── win_set
```

Copia esta carpeta a tu dispositivo. Después, en la app, al clicar `Añadir Sonidos` selecciona esta carpeta `MisSonidosExtra` y la app añadirá automáticamente todos los sonidos en cada categoría.

## Editar Sonidos Extra

Puedes editar los sonidos extra pulsando en las distintas opciones de la lista de sonidos extra de esta pantalla. Por cada sonido puedes editar su nombre, aumentar o disminuir su volumen relativo y probar cómo suena. Cuando hagas un cambio, el botón de guardado aparecerá para que puedas guardar los cambios.

Si quieres mover el sonido a otra categoría, pulsa el botón de seleccionar sonido que está a la izquierda del panel del sonido extra, y haz clic en el botón de `Mover Sonidos` que está arriba (asegúrate de que has seleccionado la categoría a la que quieres mover el sonido en el desplegable de arriba).

## Borrar Sonidos Extra

Si quieres borrar uno o varios sonidos extra, pulsa el botón de selección a la derecha del panel de cada sonido extra que quieras borrar. Después pulsa el botón `Borrar Sonidos` de la parte superior. Un popup de confirmación aparecerá para confirmar que quieres borrar los sonidos.

!!! note
    Esto NO borrará los ficheros originales, sólo la referencia que guarda internamente Contador Pádel.
