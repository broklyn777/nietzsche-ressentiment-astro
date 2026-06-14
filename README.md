# Nietzsche Ressentiment Astro

Ett litet Astro-projekt på svenska för att lära sig Astro genom att bygga en
ämnessida om Friedrich Nietzsche och begreppet ressentiment.

## Kom igång

Installera beroenden:

```bash
npm install
```

Starta utvecklingsservern:

```bash
npm run dev
```

Öppna sedan adressen som Astro skriver ut, oftast `http://localhost:4321`.

## Var du lär dig Astro

- `src/pages/index.astro` är startsidan. I Astro blir varje fil i `src/pages`
  en route.
- `src/layouts/BaseLayout.astro` är den återanvändbara HTML-ramen.
- `src/data/ressentiment.ts` innehåller textdata som sidan loopar över.
- `public/favicon.svg` serveras direkt från roten av webbplatsen.

## Nästa övningar

1. Skapa `src/pages/begrepp.astro` och länka dit från startsidan.
2. Gör en komponent `src/components/ConceptCard.astro`.
3. Lägg till en lista med frågor för egen reflektion.
4. Byt färger och typografi i layoutens globala CSS.
