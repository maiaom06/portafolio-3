# Sitio web personal — Maia Ospina

Sitio estático responsive creado con HTML, CSS y JavaScript, sin dependencias de compilación.

## Archivos
- `index.html`: estructura y contenido.
- `styles.css`: diseño, responsive y animaciones.
- `script.js`: menú móvil, filtros de proyectos y pequeños efectos de entrada.
- `assets/`: imágenes extraídas del portafolio PDF y retrato extraído de la hoja de vida.

## Vista previa local
Abre `index.html` en un navegador. Para probarlo como servidor local, desde esta carpeta ejecuta:
```bash
python3 -m http.server 8000
```
y visita `http://localhost:8000`.

## Publicación
Sube la carpeta completa (con `index.html`, `styles.css`, `script.js` y `assets/`) a un hosting estático como Netlify, GitHub Pages o el servidor de tu organización. No cambies la estructura de rutas de `assets/`.

## Antes de publicar
- Confirma que el correo, teléfono y demás datos de contacto sigan vigentes.
- Revisa la redacción del reconocimiento CLAEP: la hoja de vida menciona tercer puesto, mientras que el portafolio menciona segundo y tercer lugar. El sitio conserva esa diferencia de forma explícita para no inventar una versión.
- Añade los enlaces externos de videos o publicaciones cuando tengas sus URL definitivas; el PDF muestra llamados de “clic aquí”, pero no incluye las direcciones de destino.
- Las imágenes se extrajeron de las páginas del portafolio y se incorporaron como archivos locales.
