
npm run dev
```
Visita http://localhost:3000

## Build & produzione
```bash
npm run build
npm start
```

## Deploy consigliato: **Vercel** (1 click)
1. Crea un account su https://vercel.com
2. Clicca **New Project** → **Importa** questo progetto da Git/GitHub (oppure carica la cartella).
3. Vercel riconosce Next.js automaticamente → **Deploy**.
4. Imposta il tuo dominio (es. `italadvice.com`) in **Domains**.

## Alternative di deploy
- **Netlify** (importa repo → framework Next.js)
- **Docker** in qualsiasi VPS (Node 18+, reverse proxy Nginx)

## SEO
- Metadata in `app/layout.js` + per-pagina
- `app/sitemap.js` e `public/robots.txt`
- URL parlanti in italiano
- Aggiungi Google Analytics e Search Console dopo il deploy

## Modulo contatti
- Collega il bottone a un servizio come **Formspree** o **Getform** oppure a un backend/API.
