# Fastighetsservice Boilerplate

En snabbstart f\u00f6r att bygga statiska webbplatser med [Astro](https://astro.build/) och Tailwind CSS. Fokuserad p\u00e5 fastighetsservice, f\u00f6rvaltning och proptech.

## Struktur

```
src/
  pages/
    index.astro
    kontakt.astro
    karriar.astro
    om-oss.astro
    referenser.astro
    blogg/
      index.astro
    tjanster/
      index.astro
      forvaltning.astro
      fastighetsservice.astro
      proptech.astro
  components/
    Hero.astro
    Services.astro
    Contact.astro
    Header.astro
    Footer.astro
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

Index-sidan använder `await fetch()` för att hämta tjänstedata. Byt ut URL:en mot ditt headless CMS (t.ex. Sanity, Contentful) för att hantera innehållet dynamiskt. Samma mönster kan användas på övriga sidor.

## Nytt projekt

Kopiera hela denna mappstruktur till en ny kund och uppdatera innehållet. Boilerplaten är avskalad för snabb start och kan enkelt anpassas. Menyn definieras i `Header.astro` och kan enkelt ändras beroende på vilka sidor som ska visas.
