# Sean Nkosi – Personal Site

This repository hosts the source for [siphoxnkosi.github.io](https://siphoxnkosi.github.io), Sean Nkosi’s personal CV and portfolio site. It is based on Creative Tim’s Now UI Kit and includes custom styling and content updates tailored to Sean’s current experience.

## Structure

- `index.html` – Main page with hero, skills, portfolio, experience, education, certifications, and contact form.
- `css/` – Core theme styles (`main.css` includes the modern visual refresh).
- `js/` and `scripts/` – Vendor scripts plus site-specific behavior.
- `images/` & `files/` – Assets and downloadable résumé.

## Development

1. Open `index.html` in a browser or use a simple static-server (e.g., `python3 -m http.server`) to preview.
2. Edit HTML/CSS directly; no build step is required.
3. Keep external dependencies (fonts, icons, Bootstrap/Now UI scripts) referenced via CDN unless you plan to bundle them locally.

## Deployment

Push changes to the `main` branch (or the branch configured for GitHub Pages) and GitHub Pages will automatically rebuild the site.
