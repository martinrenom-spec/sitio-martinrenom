# Sitio de Martín Renom & Asociados

Contenido de https://martinrenom.com.ar

- `public/` es lo que se publica: `index.html` y la carpeta `img/`.
- Cada cambio que entra en la rama `main` se publica solo en Cloudflare Pages
  (proyecto `martinrenom`), mediante la tarea de `.github/workflows/publicar.yml`.
- El formulario de contacto no vive acá: lo atiende el Worker `contacto-martinrenom`
  en la ruta `martinrenom.com.ar/api/contacto`.
