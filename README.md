# Sentido Value — Landing Page

Landing page del programa **Value Builders** de Sentido Value (Sergio Cortés).

## Estructura

- `index.html` — la página completa (HTML + CSS + JS en un solo archivo; las fotos van embebidas como base64 dentro del propio HTML).
- `programa_sentido_value.mp4` — video principal del hero.
- `testimonio_camilo.mp4` — video testimonio de Camilo Gamboa.
- `favicon*.png` / `favicon.ico` — ícono del sitio.
- `og-image.jpg` — imagen de vista previa al compartir el link (WhatsApp, Facebook, etc.).

## Cómo editar el contenido

Todo el texto y estilos están en `index.html`. Es un solo archivo, sin build ni dependencias —
se puede abrir y editar directo. Para cambiar textos, busca el texto exacto y reemplázalo.

## Cómo actualizar el sitio publicado

Este proyecto está conectado a Vercel. Cualquier cambio que subas a la rama `main` de este
repositorio se publica automáticamente en unos segundos (Vercel hace redeploy solo).

## Botón de agendar reunión

Todos los botones de "agendar" apuntan a:
https://calendly.com/valuesentido/llamada-programa-sentido-value

Si cambias el link de Calendly, busca esa URL en `index.html` (aparece varias veces) y reemplázala.
