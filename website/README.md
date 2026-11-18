# Custos â€” Site Web Vitrine Officiel

Site vitrine SaaS & Pages lÃ©gales officielles de l'application Android **Custos** (`https://custos.joshuanancey.com`), conÃ§u avec **Next.js (App Router)**, **Tailwind CSS**, **Framer Motion** et **Lucide Icons**.

## Routes disponibles

- `/` â€” Landing Page officielle (Hero + Mockup Android interactif, FonctionnalitÃ©s extraites du code source, Architecture Privacy-First & SÃ©curitÃ©, FAQ, AccÃ¨s anticipÃ© Google Play)
- `/privacy` â€” Politique de confidentialitÃ© RGPD complÃ¨te & dÃ©claration transparente des permissions Android (Play Console)
- `/delete-account` â€” ProcÃ©dure dÃ©diÃ©e de suppression de compte et des donnÃ©es (exigence Google Play Data Safety)
- `/terms` â€” Conditions GÃ©nÃ©rales d'Utilisation (CGU)

## DÃ©ploiement sur Vercel (`custos.joshuanancey.com`)

1. Sur Vercel, importer le dÃ©pÃ´t GitHub `joshdeutc/custos-studio`.
2. Dans **Project Settings â†’ General â†’ Root Directory**, dÃ©finir `website`.
3. Framework Preset : **Next.js** (dÃ©tectÃ© automatiquement).
4. Build Command : `npm run build` | Output Directory : `.next` (par dÃ©faut).
5. Dans **Domains**, associer le sous-domaine `custos.joshuanancey.com` (CNAME pointant vers `cname.vercel-dns.com`).

## DÃ©veloppement local

```bash
cd website
npm install
npm run dev
```

