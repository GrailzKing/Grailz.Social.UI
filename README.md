# Grailz Flip Post Template

A single-file, no-build HTML tool for generating "flip profit" social graphics
(retail / resale / return / profit stat cards) for Instagram, TikTok, and Twitter.

## Features
- Editable eyebrow, title, subtitle, tagline — supports `*word*` accent-color highlighting
- Two image layers: a full-bleed background image + a bold foreground product shot,
  each with independent opacity and size/zoom controls
- 8 built-in color themes (pink/blue, green/white, purple/blue, amber/pink,
  teal/white, red/white, gold/black, magenta/cyan)
- Custom background image upload
- Grailz brand logo watermark (position + size configurable)
- Platform size presets: Square 1:1, Portrait 4:5, Story 9:16
- One-click "Download PNG" export (via html2canvas)
- Reset-to-defaults button

## Usage
Open `index.html` directly in any browser — no build step, no server required.
Fill in the fields on the left, pick a theme and size, then click **Download PNG**.

## Notes
- All rendering happens client-side; nothing is uploaded anywhere.
- The Grailz logo is embedded as a base64 data URI so exports work offline
  and without CORS issues.
- If you use external image URLs for backgrounds/products, note that some
  hosts block cross-origin canvas reads, which can cause the PNG export to
  fail for that image. Uploading the file directly (via the file inputs)
  always works.
