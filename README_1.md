# Cafeterías de Murcia

Una lista de cafeterías de Murcia para compartir con amigos, con la opinión de Ángela sobre cada una. Tiene un mapa con todos los sitios, un buscador, filtros por tipo y una lista personal de los que quieres probar. Los sitios que todavía no ha probado lo indican.

**Ver la web:** https://angelas482511.github.io/cafeteria-murcia/

## Qué puedes hacer

- Buscar por nombre o por tipo (por ejemplo, «postres»), sin importar los acentos.
- Filtrar por etiquetas: brunch, postres, buenos precios, café de especialidad, té o cócteles.
- Ver cada sitio en el mapa o abrirlo en Google Maps.
- Guardar los que quieres probar en «Mi lista». Se queda guardada en tu navegador.
- Usarla desde el móvil: el diseño se adapta al tamaño de la pantalla.

## Tecnologías

HTML, CSS y JavaScript sin dependencias de compilación. El mapa usa [Leaflet](https://leafletjs.com/) con datos de [OpenStreetMap](https://www.openstreetmap.org/copyright).

## Cómo añadir un sitio

Abre `index.html`, busca la lista `CAFES` y copia uno de los bloques cambiando sus datos:

| Campo | Para qué sirve |
|---|---|
| `id` | Una palabra sin espacios y distinta de las demás. |
| `nombre` | El nombre que se ve en la lista. |
| `desc` | Tu opinión sobre el sitio. Puede quedarse vacía. |
| `fui` | `true` si has ido y `false` si todavía no (aparece «Aún no he ido»). Es opcional. |
| `tags` | Las etiquetas para filtrar. |
| `lat`, `lng` | Las coordenadas. En Google Maps, haz clic derecho sobre el sitio y copia los números. |
| `q` | El texto con el que se busca el sitio en Google Maps. |

## Cómo verla en tu ordenador

Descarga el repositorio y abre `index.html` en el navegador. No hace falta instalar nada. Necesitas conexión a internet para ver el mapa y las tipografías.

## Publicarla con GitHub Pages

1. En el repositorio, entra en **Settings > Pages**.
2. En «Build and deployment», elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
3. Espera uno o dos minutos. La dirección aparecerá en la misma pantalla y será la de arriba.

## Autoría

Lista de Ángela Vega.
