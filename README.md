# Fuerza Gym — demo

Landing de una sola página, estática y sin dependencias locales. El sitio vive en `public/index.html`.

Los planes, precios, clases, equipo, cifras y reseñas son **datos de ejemplo de la demo**: se reemplazan por los reales del gimnasio antes de publicar.

## Deploy

Vercel lo toma directo: `vercel.json` fija `public` como carpeta de salida.

## Regenerar

El archivo se genera desde la plantilla de BRN Solutions (`landings/gimnasios/plantilla.mjs`). Al regenerar, copiar el `index.html` resultante a `public/`.
