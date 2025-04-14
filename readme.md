# En Tinta Verde

## El sistema de historias

El contenido del sitio está organizado en historias.

Las historias se encuentran en el folder `/content/es/stories/`. Cada carpeta lleva el nombre de la historia y corresponde a su URL en el sitio WEB.

Como ejemplo la URL de la historia compostaje-mariano-escobedo es https://entintaverde.org/stories/compostaje-mariano-escobedo/.

### Metadatos de una historia

Los metadatos de la historia nos ayudan a proporcionar por un lado información a los motores de búsqueda. Los metadatos se encuentran en la cabecera de cada historia.

#### Historias publicadas

Las historias que van a publicarse en el sitio deben tener el metadato `draft` con el valor `false`.

## Convert images

for i in *.HEIC; do sips -s format jpeg -s formatOptions 70 "${i}" --out "${i%HEIC}jpg"; done


## Resize images

mkdir -p resized && sips -Z 640 *.jpg --out resized/


## TODO

- Dynamic home cover image