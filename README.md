# Automation portfolio site

Static one-page proof site for the USD automation service. Three offers, three working demos, real sample results.

## Local preview

Open `index.html` in a browser, or:

```bash
python -m http.server 8123
```

Then open `http://localhost:8123`.

## Deploy

The site is published from this folder to GitHub Pages. The public URL is:

`https://thjntoan.github.io/automation-portfolio/`

To update, edit `index.html`, then:

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Pages rebuilds on the `main` branch.

## Contents

- `index.html`: the page, inline CSS, no external dependencies.
- `assets/l1_digest.png`, `r1_weekly_report.png`, `d1_reconciliation.png`: demo screenshots.
- `assets/og.png`: 1200x630 social preview image.
- `assets/*.zip`: the three sample builds with tests and READMEs.

All sample data is synthetic. No client, personal or employer data is used.
