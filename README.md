# IAGratis — Directorio de herramientas de IA gratuitas

Proyecto frontend estático inspirado en la idea de un directorio tipo Toolify, pero con identidad propia y centrado exclusivamente en herramientas con acceso gratuito o open source.

## Ejecutar
Abre `index.html` directamente en el navegador o sirve la carpeta con cualquier servidor estático.

Ejemplo:
```bash
python -m http.server 8080
```

## Desplegar
Compatible con Netlify, Vercel, GitHub Pages y cualquier hosting estático.

## Estructura
- `index.html` — interfaz
- `assets/style.css` — diseño responsive
- `assets/app.js` — búsqueda, filtros, categorías y ordenación
- `data/tools.js` — catálogo inicial

## Importante
El catálogo inicial es una base editable. Los planes gratuitos, límites y condiciones de las herramientas pueden cambiar. Para una versión pública conviene añadir un backend/CMS y un sistema de revisión periódica.

## Próxima evolución recomendada
1. Supabase para almacenar herramientas.
2. Panel admin para añadir/editar herramientas.
3. Filtros: 100% gratis, sin tarjeta, open source, API gratis, uso comercial.
4. Votos y favoritos.
5. Página individual SEO para cada herramienta.
6. Importador CSV/JSON.
7. Sistema automático que compruebe periódicamente si el enlace sigue activo y si mantiene plan gratuito.
8. Monetización opcional mediante afiliación, sin cobrar al usuario.
