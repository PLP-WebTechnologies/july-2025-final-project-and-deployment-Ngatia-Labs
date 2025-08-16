# BlueGold — Multipage Website (Final Project Starter)

**Color spec (requested):**
- Primary button: **Blue** (`#1e40af`), hover changes to **Yellow/Gold** (`#facc15`).
- Rest of palette chosen for high contrast, modern look, and accessibility.

## Pages
- `index.html` — Home (hero, features, CTA)
- `about.html` — About (goals & approach)
- `services.html` — Services (cards + CTA)
- `gallery.html` — Gallery (grid + lightbox)
- `contact.html` — Contact (validated form)

## Tech
- HTML5 semantic structure
- CSS (custom properties, responsive grid, animations)
- Vanilla JS (nav toggle, scroll reveal, form validation, lightbox, back-to-top)

## File Structure
```
/css/style.css
/js/main.js
/images/*.svg
index.html, about.html, services.html, gallery.html, contact.html
```

## How to Run Locally
Just open `index.html` in your browser. For best results, serve via a simple HTTP server:
- Python 3: `python -m http.server 8080` then open http://localhost:8080

## Deploy Options
### 1) GitHub Pages
- Create a public repo, push the files.
- In **Settings → Pages**, set Source to `main` branch `/root`.
- Your site appears at `https://<username>.github.io/<repo>/`.

### 2) Netlify
- Drag-and-drop the project folder into Netlify or connect your Git repo.
- Build command: none (static). Publish directory: `/`.

### 3) Vercel
- Import your Git repo on Vercel.
- Framework preset: `Other`. Output directory: `/`.

## Accessibility & Validation
- Uses semantic tags and aria attributes.
- Validate files on:
  - HTML: https://validator.w3.org/
  - CSS: https://jigsaw.w3.org/css-validator/

## Customization
- Edit colors in `:root` within `css/style.css`. Primary blue is `--primary`, hover gold is `--accent`.
- Replace images in `/images` with your own assets.
- Update text content and links as needed.