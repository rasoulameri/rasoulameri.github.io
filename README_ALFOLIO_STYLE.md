# Rasoul Ameri portfolio — al-folio-like static version

This is a drop-in static GitHub Pages version inspired by clean academic portfolio layouts such as al-folio.

## Local preview

```bash
cd ~/Downloads
unzip portfolio_alfolio_like.zip -d portfolio-test
cd portfolio-test
python3 -m http.server 8000
```

Open: http://localhost:8000

## Replace current GitHub Pages site

Copy all files in this folder into your `rasoulameri.github.io` repository root.
Keep the existing `static/media` folder because this design uses these files:

- static/media/image.6fecde0284a2bd9b17b6.png
- static/media/ET.b353436dd085855d59f6.png
- static/media/EEG.a496ef3d2c014c7e81c0.png
- static/media/ETT.73025b7ab32d132ff746.png
- static/media/Fall.1beb81768fd03c84b6a2.png
- static/media/stock.9a50a07107023177ce47.png
- static/media/RasoulAmeri.bf28886451166ca5e483.pdf

## Edit

- Main text: edit each `.html` file directly.
- Style: edit `static/css/site.css`.
- Mobile menu: edit `static/js/site.js`.

## Deploy

```bash
git add .
git commit -m "Redesign academic portfolio"
git push origin main
```
