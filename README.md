# Información de la traducción

Traducción al español de Distant Worlds 2

autor: spasmos

# Comentarios

Aunque ha coincidido con la publicación de una traducción de otro compañero jugador, esta traducción es genunina, se realizó completamente de 0 partiendo de los textos en ingles a lo largo de los meses de julio, agosto y septiembre del 2026 sin ser consciente de que ya exisitia una traducción. Como el trabajo realizado fue importante la dejo publicada.

# Instalación de la traducción

Esta traducción está preparada para **Distant Worlds 2** juego base.

## Instalación

1. Cierra Distant Worlds 2.
2. Localiza la carpeta `data` dentro de la instalación del juego.
3. Como medida de seguridad, haz una copia de esa carpeta antes de modificarla.
4. Si ya habías instalado una versión anterior de esta traducción, elimina únicamente las carpetas `data\Galactopedia\GameConcepts` y `data\Galactopedia\GameScreens`. Esto evita conservar artículos duplicados con sus antiguos nombres ingleses.
5. Copia todo el contenido de `data_es_*`.
6. Pégalo dentro de la carpeta `data` del juego y acepta **reemplazar los archivos existentes**.
7. Inicia el juego normalmente.

En una instalación de GOG, la ruta puede ser:

```text
C:\GOG Games\Distant Worlds 2\data
```

La ruta puede variar si el juego está instalado en otra ubicación o mediante otra tienda.

## Actualización

Para instalar una revisión posterior de la traducción, repite el proceso, incluida la limpieza de las dos carpetas de Galactopedia, y vuelve a reemplazar los archivos. No es necesario reinstalar el juego.

## Limitación conocida: resumen inicial de la partida

Al comenzar una partida nueva, la ventana que presenta la facción, el gobierno, la especie, el líder y el mundo natal puede mostrar en inglés parte de las frases que enlazan esos datos. Los nombres y valores introducidos en ellas sí pueden aparecer traducidos, por lo que el resultado puede mezclar ambos idiomas.

Esto no indica una instalación incorrecta ni que falten archivos por copiar. Las plantillas equivalentes de `GameText.txt` están traducidas, pero esta ventana genera su texto mediante una implementación interna y protegida del juego que no utiliza completamente los textos modificables de la carpeta `data`. La traducción no puede corregir esas frases sin modificar el código del juego.

## Limitación conocida: dos títulos del menú Tutoriales

En el menú `Tutoriales`, las opciones `Ship Design Screen` y `Research Screen` permanecen en inglés. El juego utiliza el mismo campo `Title` como texto visible y como identificador interno de los botones de ayuda de esas pantallas. Si se traducen, el menú queda completamente en español, pero dichos botones dejan de abrir sus recorridos.

Se mantienen esos dos títulos ingleses para conservar la funcionalidad. Los otros once títulos del menú y todo el contenido de los recorridos están traducidos.

## Restauración

Para recuperar los textos originales, restaura la copia de seguridad de `data`. También puedes usar la opción de verificar o reparar los archivos del juego desde la tienda donde lo instalaste.
