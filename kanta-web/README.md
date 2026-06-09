# Kanta ♯ — academiakanta.com

Web oficial de Kanta, academia de música 100% online. Construida con Astro, desplegada en Cloudflare Pages.

**Toca. Escribe. Kanta.**

## Desarrollo local

```bash
npm install
npm run dev      # abre http://localhost:4321
npm run build    # genera el sitio en /dist
```

## Antes de publicar (buscar "TODO" en el código)

- [ ] `src/pages/index.astro`: número real de WhatsApp y link de Cal.com/Calendly
- [ ] `src/pages/index.astro`: precios reales (S/ XXX) y tu bio + foto
- [ ] `src/layouts/Layout.astro`: imagen og-image.png y analytics

## Deploy en Cloudflare Pages

1. Sube este repo a GitHub.
2. En Cloudflare: Workers & Pages → Create → Pages → Connect to Git.
3. Preset: Astro · Build: `npm run build` · Output: `dist`.
4. Custom domains → agrega `academiakanta.com` y `www`.

Cada `git push` a main publica automáticamente.
