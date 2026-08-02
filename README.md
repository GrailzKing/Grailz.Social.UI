# Grailz Drop Poster

**[👉 Click here to open the live tool](https://grailzking.github.io/Grailz.Social.UI/)**

A single-file, no-build HTML tool for generating "Grailz Drop" stat-card graphics
(retail / resale / return / profit) for Instagram, TikTok, and Twitter.

## How to use it

1. **Open the tool** — click the live link above (or open `index.html` directly
   in any browser). No install, no account, nothing to build.
2. **Fill in the Content section**
   - Eyebrow, Title, Subtitle, and Tagline are all editable text fields.
   - Wrap any word in asterisks to color it with your theme's accent color —
     e.g. typing `GRAILZ DROP *ARTIST*` colors just "ARTIST."
   - Pick a **Font style** from the dropdown (Rockstar, Popstar, Country,
     Grunge, EDM, Luxury, Script, Stadium, and more) to instantly change the
     whole poster's typographic vibe.
3. **Enter your Stats**
   - Type in **Retail** (cost) and **Resale** price.
   - **Return** and **Profit** calculate automatically — no manual math.
4. **Pick a Theme**
   - Click any of the 16 color swatches to set the poster's accent colors.
5. **Add your Media** (all under the collapsible "Media" section)
   - **Background image** — a full-bleed image behind everything, with its
     own opacity and zoom sliders.
   - **Main product image** — your hero shot (album cover, sneaker, figure,
     etc.), with its own opacity and size sliders.
   - **Custom poster background** — an optional full replacement background,
     also with opacity and zoom controls.
   - **Grailz logo** — toggle it on/off, choose a corner, and set its size.
   - For any image field you can either paste a URL or use the file upload
     button to pick an image from your device.
6. **Choose a Platform size**
   - Square 1:1 (Instagram feed), Portrait 4:5, or Story 9:16
     (Instagram/TikTok Stories, Reels).
7. **Download**
   - Click **Download PNG** to export the poster at full resolution, ready
     to post.
   - Click **Reset to defaults** at any time to start over.

Every section header (Content, Stats, Theme, Media, Platform size) can be
collapsed by clicking on it, so you can hide the parts you're not currently
editing.

## Features
- Editable eyebrow, title, subtitle, tagline — supports `*word*` accent-color highlighting
- 10 genre font presets (Rockstar, Popstar, Country/Western, Grunge/Punk,
  Street/Hip-Hop, EDM/Futuristic, Elegant/Luxury, Script/Signature,
  Stadium/Varsity, plus the default)
- Auto-calculated Return and Profit stats from Retail and Resale
- Two image layers — a full-bleed background image + a bold foreground
  product shot — each with independent opacity and size/zoom controls
- 16 built-in color themes
- Custom poster background image with its own opacity/zoom controls
- Grailz brand logo watermark (show/hide, position, size)
- Platform size presets: Square 1:1, Portrait 4:5, Story 9:16
- Collapsible panel sections for a cleaner editing experience
- One-click "Download PNG" export (via html2canvas)
- Reset-to-defaults button

## Notes
- All rendering happens client-side; nothing is uploaded anywhere.
- The Grailz logo is embedded as a base64 data URI so exports work offline
  and without CORS issues.
- If you use external image URLs for backgrounds/products, note that some
  hosts block cross-origin canvas reads, which can cause the PNG export to
  fail for that image. Uploading the file directly (via the file inputs)
  always works.
