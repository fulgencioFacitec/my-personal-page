# My Personal Page

Portafolio personal de **Oscar Duarte** — Ingeniero de Software.

- Estilo basado en https://my-personal-page-hazel.vercel.app/
- Stack: HTML5, CSS3 (Outfit, glassmorphism, gradientes), FontAwesome
- Deploy: [Vercel](https://vercel.com) conectado a GitHub (`fulgencioFacitec/my-personal-page`)

## Desarrollo local

```bash
# Opción 1: Python
python -m http.server 8000

# Opción 2: Node serve
npx serve .

# Opción 3: Vercel CLI (requiere login)
npx vercel dev
# luego abrir http://localhost:3000
```

Luego abrir http://localhost:8000

## Deploy en Vercel

El proyecto está configurado como Static (sin build). Vercel despliega automáticamente cada `git push` a `main`:

- Dashboard: https://vercel.com/facitec/my-personal-page
- Dominio producción: `my-personal-page-wine.vercel.app` (según captura)

Para deploy manual:

```bash
npx vercel --prod
```

## Estructura

```
.
├── index.html
├── style.css
├── vercel.json
└── assets/avatar.jpg
```
