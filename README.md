# Triquestra Solutions – Portfolio Website

A modern, responsive, multi‑page static website for Triquestra Solutions.

## Quick start

- Open `index.html` in your browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Structure

- `index.html` – Home
- `services.html` – Services overview and details
- `work.html` – Portfolio/case studies
- `about.html` – Company and team
- `contact.html` – Contact form and details
- `assets/css/styles.css` – Core styles
- `assets/js/main.js` – Navigation and form logic
- `assets/img/logo.svg` – Logo

## Customize

- Brand: Update name, colors, and logo in `assets/css/styles.css` and `assets/img/logo.svg`.
- SEO: Update meta tags in each HTML file.
- Contact form: By default it uses normal form post/mailto. To enable Formspree, set `data-endpoint` on `#contact-form` to your endpoint, e.g.

```html
<form id="contact-form" data-endpoint="https://formspree.io/f/yourid">...</form>
```

## Deploy

- GitHub Pages, Netlify, or any static host. Just upload the files.

## License

© Triquestra Solutions. All rights reserved.
