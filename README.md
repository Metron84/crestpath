# Crest Paths

The Crest blueprint as an installable PWA: every club, every tap, every route home.

- 183 clubs across 17 leagues, with chip, room share and the 18-tap file path.
- 25 reroutes for clubs that miss on a straight file path.
- Live findings, card pressure, gravity wells, full explorer and fix list.
- Works offline after first load; installs to the home screen on iOS and Android.

## Run locally

```bash
npx serve .
```

## Deploy

Static site, no build step. Import the repo in Vercel and deploy with default settings.

## Update the data

Club paths live in `RAW` and reroutes in `RR` inside `index.html`.
Bump `CACHE` in `sw.js` after any change so installed copies refresh.
