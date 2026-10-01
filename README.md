# Crest Paths

What to tap to land each club in The Crest.

- One club at a time: country, first chip, five Life cards, five doors, then the rest.
- **To land this club** is the default. Misses use the 25 reroutes.
- **Straight file path** shows the vector path, even when it loses.
- 183 clubs, 25 different routes. Works offline after first load.

## Run locally

```bash
npx serve .
```

## Deploy

Static site, no build step. Import the repo in Vercel and deploy with default settings.

## Update the data

Club paths live in `RAW` and reroutes in `RR` inside `index.html`.
Bump `CACHE` in `sw.js` after any change so installed copies refresh.
