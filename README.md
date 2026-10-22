# Bake Me A Wish

A festive, premium gifting landing page for Diwali-inspired sweets and curated hamper boxes. The project is built as a single-page storefront with polished visuals, a product collection, a hamper packaging gallery, an interactive hamper builder, and direct WhatsApp ordering.

## Overview

Bake Me A Wish is designed to feel warm, premium, and celebratory. The page highlights handcrafted sweets, curated gifting bundles, and a modern storefront aesthetic suited for seasonal gifting campaigns.

## Features

- Elegant hero section with strong festive branding
- Curated product gallery for premium sweet, snack, and festive hamper items
- Hamper packaging gallery showcasing available festive presentation styles
- Auto-rotating, seamless infinite photo gallery with manual arrows, dots, touch swipes, and keyboard controls
- Interactive hamper builder for selecting treats and placing orders with packaging details included
- Responsive layout for mobile and desktop screens
- Direct WhatsApp ordering links for quick customer conversion
- Vercel Web Analytics integration
- Optional playing cards at ₹250 per deck and festive diyas at ₹80 per diya
- Premium packaging upgrade at ₹400
- Ready-made hamper combinations with one-tap ordering
- Sold-out hamper cards with their latest product photos
- Story, testimonial, and gallery sections to reinforce the gifting experience

## Project structure

- `index.html` — main page structure, styles, and interactive JavaScript
- `logo.png` — brand logo asset
- `HappyDiwaliAudio.mp3` — optional low-volume background audio
- Product image assets — product and packaging photography used throughout the storefront
- `README.md` — project overview and usage instructions

## Local preview

Because this project is a static front-end site, you can run it in any browser without installing dependencies.

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Serve locally

From the project root, run:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Customization

You can easily adapt the project by editing:

- Product names, pricing, and catalog entries in the `hamperCatalog` array inside `index.html`
- WhatsApp order links in the page and builder actions
- Branding, colors, and typography variables in the CSS at the top of `index.html`
- Gallery photos in the `gallery-track` markup; the gallery auto-rotates in a seamless infinite loop and also supports arrows, dots, touch swipes, and keyboard controls

## Notes

This project is intentionally lightweight and dependency-free, making it ideal for quick deployment as a static marketing or storefront landing page.

Packaging details are also included in the storefront and may vary by availability, with a standard packaging charge of ₹250, delivery fees at actuals, last order date 25th October, and outstation hampers dispatched between 28th and 30th October.

## Contact / business link

The storefront includes WhatsApp ordering links that point to the business number configured in the page:

- `+91 77059 82880`
