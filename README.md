# DentalClinicApp

A generic single-page landing site for dental clinics. Built as a reusable starting point — future versions will be customized per client (branding, copy, photos, colors).

## What it is

A static, single-file HTML page recreating a typical dental clinic landing page based on a real reference design. No build step, no framework — just open `index.html` in a browser.

## Sections

1. **Top nav bar** — logo, primary links, WhatsApp CTA, contact info
2. **Hero** — clinic name + tagline + "Agenda una cita" button, with a fixed-background parallax effect
3. **Especialidades Odontológicas** — 8 dental specialty cards in a 3-column grid
4. **Banner** — years-of-experience highlight with image and CTA
5. **Nuestro Trabajo** — 3x3 grid of treatment photos
6. **Nuestros Pacientes Opinan** — Google review cards
7. **Final CTA** — "Agende una cita" closer
8. **Footer** — schedule, location + map, full navigation, contact form
9. **Floating WhatsApp button**

## Tech stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) via CDN (no build step)
- Custom CSS for the parallax hero, decorative underlines, and gradient details
- [Google Fonts](https://fonts.google.com/) — Roboto, Roboto Slab
- Placeholder images from [picsum.photos](https://picsum.photos)

## Running locally

Just open the file:

```bash
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

No install required.

## Screenshot tooling

A small Puppeteer script is included for rendering full-page screenshots while iterating on the design.

```bash
npm install
node screenshot.js
```

This writes `screenshot.png` so you can compare the rendered page against a reference image.

## Roadmap

This is the **generic template**. Per-client work will swap:

- Brand colors, logo, fonts
- Real clinic photos (hero, work grid, team)
- Copy, services, locations, schedule
- Real Google Maps embed and live review feed
- Working contact form backend (currently inert)
- Custom domain and deployment

## License

Private / unlicensed for now.
