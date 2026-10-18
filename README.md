# Spancraft homepage

Holding page for [spancraft.in](https://spancraft.in): the Spancraft logo over an endless, slowly moving vault of line-drawn arches, with "Coming soon".

Plain static site, no build step. Preview locally with `python3 -m http.server 8790` and open http://localhost:8790.

- `index.html` — page, styles, and the canvas animation (constants at the top of the script set spacing, speed, and accent frequency).
- `assets/` — logo, favicon, and the Outfit font, copied from `spancraft/admin` brand files.
- `CNAME` — custom domain for GitHub Pages.

Served by GitHub Pages from `main`. Pushing to `main` updates the live site.
