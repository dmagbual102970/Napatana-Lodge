# Napatana Lodge — demo website

**Demo only. Sample content. No backend.** Built to show what the lodge's website could look like.

- **Live:** https://dmagbual102970.github.io/Napatana-Lodge/
- **Theme:** forest green · Playfair Display + Inter
- **Hero:** aerial photo of the lodge (watermark cropped)
- **Contact:** +675 7369 7720 · WhatsApp · Alotau, Milne Bay Province
- **Demo content:** sample rooms (Standard K450, Garden K550, Family K650), services with photos,
  "why book direct" section, sample policies, guest stories.
- **Demo booking:** the booking wizard, availability check and "find my booking" are answered locally
  (no Firebase) so the flow can be demonstrated end to end. Receipts/payments are not collected.

## Rebuilding

```bash
cd "Edgewood Hotel & Apartment/website"
VITE_DEMO_CONTENT=true node ./node_modules/vite/bin/vite.js build --base=/Napatana-Lodge/
```

Copy `dist/` here, copy `index.html` to `404.html`, keep `.nojekyll`.

## Routes

`/` · `/rooms` · `/services` · `/past-events` · `/about` · `/contact` · `/policies` ·
`/function-hall` · `/restaurant-cafe` · `/book` · `/booking-lookup`
