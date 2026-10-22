# Napatana Lodge — demo website

**Demo only.** Static build of the Edgewood Hotel & Apartment website, saved here as the demo
starting point. No Firebase project is connected yet.

- **Live demo:** https://dmagbual102970.github.io/Napatana-Lodge/
- **Source:** the private repo `dmmagbual/Edgewood-Hotel-and-Apartment` (`website/` app)
- **Content:** every room, rate, photo, event and contact detail is **sample content**.
- **Backend:** none in this build. The booking wizard, availability and "find my booking" screens
  show their empty states. Firebase (Firestore + Cloud Functions) will be connected later.

## Rebuilding for this repo

```bash
cd "Edgewood Hotel & Apartment/website"
node ./node_modules/vite/bin/vite.js build --base=/Napatana-Lodge/
```

Copy `dist/` to the repo root, copy `index.html` to `404.html` (SPA fallback for GitHub Pages),
and keep `.nojekyll`.

## Routes

`/` · `/rooms` · `/services` · `/function-hall` · `/restaurant-cafe` · `/past-events` ·
`/about` · `/contact` · `/policies` · `/book` · `/booking-lookup`
