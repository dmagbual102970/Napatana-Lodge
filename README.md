# Napatana Lodge — demo website

**Demo only. Sample content.** Static build of the Napatana Lodge website, hosted on GitHub Pages.

- **Live demo:** https://dmagbual102970.github.io/Napatana-Lodge/
- **Theme:** deep forest green · Playfair Display + Inter
- **Hero:** aerial photograph of the lodge (watermark cropped)
- **Contact shown:** +675 7369 7720 · WhatsApp button · Alotau, Milne Bay Province
- **Content:** sample rooms (Standard K450, Garden K550, Family K650), service cards with photos,
  "why book direct" section, sample policies — to be confirmed with the lodge.
- **Backend:** none. Booking/availability/find-my-booking are visual demo flows until Firebase
  (Firestore + Cloud Functions) is connected.

## Rebuilding

```bash
cd "Edgewood Hotel & Apartment/website"
VITE_DEMO_CONTENT=true node ./node_modules/vite/bin/vite.js build --base=/Napatana-Lodge/
```

`VITE_DEMO_CONTENT=true` shows the sample rooms/rates when Firestore is empty.

Copy `dist/` here, copy `index.html` to `404.html`, keep `.nojekyll`.

## Routes

`/` · `/rooms` · `/services` · `/past-events` · `/about` · `/contact` · `/policies` ·
`/function-hall` · `/restaurant-cafe` · `/book` · `/booking-lookup`
