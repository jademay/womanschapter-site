# Woman's Chapter

A static website built with plain HTML, CSS, and JavaScript.

## Local preview

Open `index.html` in a browser, or run a simple local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Structure

- `index.html` — page markup
- `styles.css` — styling
- `script.js` — interactivity
- `CNAME` — GitHub Pages custom domain (`womanschapter.co.uk`)

## Images to add

The hero workbook mockup and the "Is this for you?" lifestyle image are currently CSS placeholders. To replace them:

1. Add an `images/` folder.
2. Drop in your workbook mockup (e.g. `images/workbook.png`) and lifestyle photo (e.g. `images/calm-corner.jpg`).
3. In `index.html`, replace the `.workbook-mockup` and `.image-placeholder` blocks with `<img>` tags pointing at those files.
