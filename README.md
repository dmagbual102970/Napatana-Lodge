# Napatana Lodge — demo website

**Demo only. Sample content.** Static build of the Napatana Lodge website, hosted on GitHub Pages.
No Firebase project is connected yet.

- **Live demo:** https://dmagbual102970.github.io/Napatana-Lodge/
- **Content:** sample rooms, policies and copy — to be confirmed with the lodge. Photos are sample imagery.
- **Contact shown:** +675 7369 7720 (from the PNG hospitality lead list) · Alotau, Milne Bay Province
- **Backend:** none in this build. The booking wizard, availability and "find my booking" show their
  empty states until Firebase (Firestore + Cloud Functions) is connected later.

## Rebuilding

```bash
cd "Edgewood Hotel & Apartment/website"
node ./node_modules/vite/bin/vite.js build --base=/Napatana-Lodge/
```

Copy `dist/` here, copy `index.html` to `404.html` (SPA fallback), keep `.nojekyll`.

## Routes

`/` · `/rooms` · `/about` · `/contact` · `/policies` · `/book` · `/booking-lookup`
