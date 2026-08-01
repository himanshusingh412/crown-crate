# Crown Crate

**Unbox Royalty. Feel the Love.**

Luxury gift-hamper storefront for Crown Crate — hand-packed hampers for weddings,
birthdays, festivals, corporate gifting and everything in between.

## What's here

| File | Purpose |
| --- | --- |
| `index.html` | The complete single-file storefront (HTML + CSS + JS) |
| `assets/` | Logo derivatives, favicons, apple-touch icon |

## Features

- **Cinematic 3D hero** — a Three.js champagne crate that opens as you scroll: the lid
  lifts, the ribbon unwinds and the contents rise, with gold dust and floating petals.
  Falls back to a photographic hero when WebGL or motion is unavailable.
- **Premium loading screen** with animated logo, golden shimmer and progress.
- **Full commerce surface** — featured categories, best sellers, luxury collections,
  personalised gifts, filterable occasion grid (occasion + budget), reviews rail,
  video testimonials, about, why-us with counting stats, corporate quote form,
  live gift customizer, FAQ, Instagram gallery, newsletter and footer.
- **Shopping UX** — cart drawer, wishlist, quick view, quick buy, gift message,
  gift wrap, delivery date, search overlay and toasts.
- **Accessible & responsive** — WCAG-AA contrast, visible focus states, keyboard
  traps in overlays, `prefers-reduced-motion` support, 375 → 1440px breakpoints.

## Running it

No build step. Open `index.html`, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Before going live

1. **Product photography** — images are currently royalty-free Pexels placeholders.
   Replace the image IDs in the `PRODUCTS`, `CATS`, `COLLS`, `VIDS` and `IG` arrays
   inside `index.html` with real Crown Crate shots.
2. **Checkout** — the checkout button is a demo. Wire in a payment gateway
   (Razorpay / Stripe) or route orders to WhatsApp.
3. **Forms** — the corporate quote and newsletter forms validate client-side only.
   Point them at a backend or form service.

## Contact

Kartik · [kartikv627@gmail.com](mailto:kartikv627@gmail.com) · +91 91491 81502
· [@crowncrate_kartik](https://instagram.com/crowncrate_kartik) · Ghaziabad, Uttar Pradesh
