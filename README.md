# uipath-technical-partner-success.github.io

Root of the org's GitHub Pages domain. Every other site lives at `/<repo>/` and is served from its own public repo.

- `index.html` is the public **Useful partner links** page (the link in our email signatures). It features the
  [Trainings Dashboard](https://uipath-technical-partner-success.github.io/Trainings-Dashboard/trainings-dashboard.html)
  and the Partner Success Service Desk, then lists partner and general UiPath links. Light by default, with a dark toggle.
- `404.html` handles any path that no site matches. A mistyped case (e.g. `/ixp-handsonworkshop/`) or an old site name
  (`/IXP-AdvancedWorkshop/`) is redirected to the right site; anything else gets a "not found" page with a link to the dashboard.
  **When you add or rename a public site, update `SITES` / `OLD` in `404.html`.**

This repo is public. Nothing internal or partner-specific goes here.
