# Analitix Web (Astro + Tailwind)

## Requisitos
- Node 20+

## Scripts
```bash
npm ci
npm run dev
npm run build
npm run preview
```

## Deploy a Surfer (Cloudron)
1. `npm run build` → genera `dist/`.
2. En Surfer, crea un sitio y sube el contenido de `dist/`.
3. (Opcional) Configura WebDAV y un workflow de GitHub Actions para automatizar.

## Siguientes pasos
- Añadir formulario en `/contacto` con POST a webhook n8n.
- Agregar páginas de servicios, casos y blog.
- Configurar GA4 + consent mode.
