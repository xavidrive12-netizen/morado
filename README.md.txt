# Morado — Sitio web (estático)

Web estática para el restaurante **Morado** (Requena). Diseñada para publicarse en GitHub Pages o cualquier hosting estático.

## Contenido
- `index.html` — página única, responsive, con secciones: inicio, menú, reservas, ubicación, contacto.
- `assets/` — carpeta opcional para imágenes y logo.

## Publicar en GitHub Pages
1. Crea un nuevo repositorio en GitHub y sube todos los archivos.
2. En Settings → Pages elige la rama `main` y la carpeta `/ (root)` y guarda.
3. GitHub generará una URL `https://<tuusuario>.github.io/<repositorio>/`.

## Notas
- El formulario de reservas usa `mailto:` por defecto. Para recibir reservas de forma automática, reemplaza el `action` por un endpoint (Formspree, Netlify Forms o una API propia).
- Personaliza textos, teléfono, horarios y fotos en `index.html`.
