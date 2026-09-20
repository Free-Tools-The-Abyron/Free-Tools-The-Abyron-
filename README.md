# FreeTools — GitHub Pages Ready

A static, local-first tools website. The dashboard/home page contains only the intro and popular tools; every category is a separate menu route/page as requested.

## Included
- Images: compressor, JPG/PNG converter, resize, crop, WebP export
- PDF: images → PDF; safe compatibility placeholders for arbitrary PDF merge/split/rendering
- Text: word counter, case converter, duplicate-line remover, Base64
- Calculators: percentage, age, EMI, GST, discount, unit conversion
- Utilities: QR, password, UUID, color picker, JSON formatter

## Deploy to GitHub Pages
1. Create a repository.
2. Upload every file/folder in this project.
3. Settings → Pages → Deploy from branch → main → /(root).
4. Open the generated Pages URL.

No build command is required.

## Important technical note
This project intentionally has no external runtime APIs or CDN dependencies. Image processing, calculators, text tools, QR generation and basic PDF creation run in the browser. Fully general arbitrary-PDF merge/split/rendering requires a full PDF parser/renderer library; the site does not pretend otherwise.
