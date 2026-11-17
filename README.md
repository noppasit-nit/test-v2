# Malee vs Tipco – Competitor Dashboard (Mockup v3)

A static, single-page dashboard comparing Malee and Tipco juice SKU pairs across Thai retailers (Lotus's, Big C): Key Insights (priority action cards), Overview with per-retailer Malee vs Tipco cards, promo patterns and promo timeline, price index vs target band, promotions log, learning cases and campaign sentiment. Filters for category, SKU, brand and retailer default to **All** (compare each); **Average** combines items into one value or line.

**Live site:** https://noppasit-nit.github.io/test-v2/

## ⚠️ MOCKUP DATA
Most figures on this page are **simulated for demonstration**. The SKU pairs are real products (each links to a public retailer listing proving it exists), but price history, promotions and target bands are MOCKUP. Only the 17 Nov 2026 shelf prices of the 3 original 1 L pairs (apple, pomegranate, coconut) at Lotus's / Big C are REAL, and are tagged REAL with source links. Do not use this page for pricing decisions.

## Data and privacy
Public data only (retailer product pages, public news and company releases, public X posts summarised by hand). No personal data, no logins, no API keys or secrets, no tracking. The page makes no network calls except the source links you choose to click.

## How to view
- Online: open https://noppasit-nit.github.io/test-v2/ (GitHub Pages: Settings → Pages → Deploy from branch → `main` / root).
- Locally: in this folder run `python3 -m http.server 8000` and open http://localhost:8000/.

## Files
- `index.html` – page shell
- `assets/app.js` – prebuilt bundle (React + dashboard); no build step needed on GitHub
- `assets/style.css` – base styles
- `.nojekyll` – tells GitHub Pages to serve files as-is

## How to remove
- Unpublish only: repo Settings → Pages → set Source to "None" (or unpublish site).
- Delete everything: repo Settings → General → Danger Zone → **Delete this repository**, then type the repo name to confirm.
