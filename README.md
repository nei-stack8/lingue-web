# Lingue Arquitectura — sitio web

Sitio de [linguearq.cl](https://linguearq.cl): página única con presentación, servicios, portafolio de proyectos y contacto.

## Estructura

- `index.html` — toda la página (HTML, estilos y script en un solo archivo).
- `img/` — fotos de proyectos y logo.
- `netlify.toml` — configuración de publicación en Netlify.

## Cómo editar

- **Textos:** se cambian en `index.html`. Las descripciones de proyectos están en la lista `P` dentro del `<script>` al final del archivo.
- **Agregar un proyecto:** subir sus fotos a `img/` con el nombre `nombreproyecto-1.jpg`, `nombreproyecto-2.jpg`, etc., y agregar una línea a la lista `P` con `id`, cantidad de fotos (`n`), categoría (`b2b`, `inmo` o `part`), título (`t`) y descripción (`d`).

## Publicación

El sitio está en Netlify, con el dominio `linguearq.cl` registrado en NIC Chile y los DNS apuntando a Netlify (`dns1`–`dns4.p02.nsone.net`).
