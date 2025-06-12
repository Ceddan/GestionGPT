# Fastighetsservice Boilerplate

En snabbstart f\u00f6r att bygga statiska webbplatser med [Astro](https://astro.build/) och Tailwind CSS. Fokuserad p\u00e5 fastighetsservice, f\u00f6rvaltning och proptech.

## Struktur

```
src/
  pages/
    index.astro
  components/
    Hero.astro
    Services.astro
    Contact.astro
  layouts/
    BaseLayout.astro
```

## Kom ig\u00e5ng

Installera beroenden och starta utvecklingsservern:

```bash
npm install
npm run dev
```

## Deploy

Projektet kan enkelt deployas till Netlify eller Vercel:

- **Netlify:** Skapa ett nytt projekt och l\u00e5t build-kommandot vara `npm run build` och publish-mappen `dist`.
- **Vercel:** Importera repot och anv\u00e4nd standardinst\u00e4llningar (`npm run build`).

## CMS-integration

Index-sidan anv\u00e4nder `await fetch()` f\u00f6r att h\u00e4mta tj\u00e4nstedata. Byt ut URL:en mot ditt headless CMS (t.ex. Sanity, Contentful) f\u00f6r att hantera inneh\u00e5llet dynamiskt.

## Nytt projekt

Kopiera hela denna mappstruktur till en ny kund och uppdatera inneh\u00e5llet. Boilerplaten \u00e4r avskalad f\u00f6r snabb start och kan enkelt anpassas.
