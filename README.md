# Sean Nkosi – Personal Site (and Playground)

This repo powers [siphoxnkosi.github.io](https://siphoxnkosi.github.io), the CV/portfolio of Sean Nkosi: developer by trade, consultant by habit, serial offender of the “just one more tweak” commit. It rides on Creative Tim’s Now UI Kit with custom styling that makes it feel like my site and not a template I swore I wouldn’t fork at 2 a.m.

## Structure

- `index.html` – Main page with hero, skills, portfolio, experience, education, certifications, and contact form.
- `css/` – Core theme styles (`main.css` includes the modern visual refresh).
- `js/` and `scripts/` – Vendor scripts plus site-specific behavior.
- `images/` & `files/` – Assets and downloadable résumé.

## Development

1. Open `index.html` in a browser or use a simple static-server (e.g., `python3 -m http.server`) to preview.
2. Edit HTML/CSS directly; no build step is required.
3. Keep external dependencies (fonts, icons, Bootstrap/Now UI scripts) referenced via CDN unless you plan to bundle them locally.

## Deployment (a.k.a. Living on the Edge)

- Push to `main` like you mean it. Yes, really. GitHub Pages rebuilds automatically, and I promise to act surprised if I break production.
- If you do open a PR, I’ll probably merge it from my phone while “consulting” on a client call. Multitasking is a skill, right?

## About the Human Behind the Commits

- Developer: writes tests, sometimes even before the bug report. Loves deleting code more than writing it.
- Consultant: fluent in stakeholderese; can diagram your architecture on a napkin and expense the napkin.
- Version control philosophy: “Move fast and make backups” — preferably in that order.
