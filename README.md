# Elite Stays Holiday Homes

A standalone, responsive room-rental operations dashboard recreated from the
public Glide app. It includes the owner dashboard, booking and room timers,
expense tracking, team directory, local persistence, dark mode, and CSV
exports.

## Run locally

Open `index.html` in a browser, or serve the folder with any static web server:

```bash
python -m http.server 8080
```

Then visit <http://localhost:8080>.

## Publish

This is a static site and can be published with GitHub Pages, Netlify, Vercel,
or any static hosting provider. For GitHub Pages, enable **Settings →
Pages → Deploy from a branch**, select `main` and `/ (root)`.

The app stores demo data in the browser's `localStorage`. Connect the form
handlers to a real API/database before using it for production records.
