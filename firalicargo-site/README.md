# Firali Cargo — website

One-page animated website (Uzbek + Russian) for Firali Cargo's courier e-scooter rental.

- `index.html` — the whole page (HTML, CSS and JavaScript in one file)
- `assets/` — logo images cut from `assets/logo-original.jpg`, plus the favicon

## Preview
Open `index.html` in a browser, or run a local server from this folder:

    python3 -m http.server 8000   # then open http://localhost:8000

## Publish
Upload this folder (`index.html` + `assets/`) to any static host (Netlify, Vercel, GitHub Pages, cPanel hosting, etc.).

## Common edits
- **Price per day:** change `PRICE_PER_DAY` near the top of the `<script>` in `index.html`.
  Plan totals (1 day, 1 week, 2 weeks, 1 month = 30 days), the calculator, FAQ answer and
  the scrolling banner update automatically. Also update the `<meta name="description">` text.
- **Working hours:** `OPEN_HOUR` / `CLOSE_HOUR` in the same place (Tashkent time). The
  "open now / closed" badge uses them.
- **Russian text:** the `RU` object in the script. Uzbek text lives directly in the HTML.
- **Colors:** `--blue` (Pantone 19-4052 Classic Blue, `#0F4C81`) and `--green`
  (Pantone 361 C, `#43B02A`) at the top of the `<style>` block.
