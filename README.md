# Gabriel Fulgencio Duarte Giménez — Personal Page

Liquid glass minimalista. Deploy estático en Vercel conectado a GitHub `fulgencioFacitec/my-personal-page`.

- **Nombre:** Gabriel Fulgencio Duarte Giménez — Estudiante Ingeniería de Software, FACITEC
- **Estilo:** Liquid glass (backdrop-filter blur 20px + saturate, translucent, soft orbs) — minimalista, tipografía Inter, layout aireado
- **Stack:** HTML5 + CSS3 puro, FontAwesome 6.5, Google Fonts (Inter + JetBrains Mono)
- **Origen:** Evolución del ejemplo `my-personal-page-hazel.vercel.app` hacia identidad propia

## Habilidades destacadas

Evaluación desde uso real de OpenCode (Muse Spark):

- **Programación Junior:** HTML semántico, CSS moderno (Flex/Grid), JS ES6+, Python básico. Código legible y Git atómico.
- **Flujo OpenCode:** Workspace local en VS Code, `plan → build`, verificación `python -m http.server` / `npx vercel dev`, Vercel CLI 59.x, Node 24.
- **Arquitectura & Hardware:** Fascinación por ISA, pipelines, jerarquía de memoria (RAM/caché), buses, I/O y ensamblaje. De la "matriz del infierno" al aislamiento con Docker/contenedores.

## Desarrollo local

```bash
python -m http.server 8000
# o
npx serve .
# o con Vercel
npx vercel dev   # http://localhost:3000 (requiere vercel link)
```

Abrir http://localhost:8000

## Deploy Vercel

Static, `vercel.json` con `cleanUrls: true`. Auto-deploy en cada `git push` a `main`:

- Dashboard: https://vercel.com/facitec/my-personal-page
- Producción: `my-personal-page-wine.vercel.app`

Manual:
```bash
npx vercel --prod
```

## Estructura

```
.
├── index.html  # liquid glass hero + skills + enfoque
├── style.css   # orbs, glass, responsive
├── vercel.json
└── assets/avatar.jpg (legacy, no requerido — avatar es inicial GD en CSS)
```
