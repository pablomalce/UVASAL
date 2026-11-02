# UVASAL

Static, multi-page rebuild of the Argentine consumer website for Uvasal, an over-the-counter antacid brand marketed by GSK. Spanish-language content.

## Context

Built between late January and early February 2021 (two commits: 2021-01-29 and 2021-02-08). The repository does not record whether the site was commissioned, so treat it as an early front-end project: a hand-coded HTML/CSS reproduction of an existing brand site. Uvasal and GSK names, logos and legal copy belong to their owners; this is not an official GSK repository.

## What it does

Nine static pages sharing one navbar and footer:

- `index.html` – home with a Bootstrap carousel of product flavours
- `productos.html` – product range and presentations
- `que_es_la_acidez.html` – explainer on heartburn
- `preguntas_frecuentes.html` – FAQ
- `prospecto.html` – product leaflet text
- `contacto.html` – public consumer-care contact details
- `aviso_legal.html`, `politica_de_privacidad.html`, `declaracion_de_audiencia.html` – legal pages

No JavaScript of its own, no forms, no build step.

## Stack

HTML5, CSS split into per-section component files (`style/componentes/*.css`), Bootstrap 4.5.2, jQuery 3.5.1 and Popper.js loaded from CDNs, Google Fonts (Oswald, Open Sans).

## Repository layout and how to view it

The two branches have separate histories:

- `main` holds only the nine HTML files, so pages render without styles or images.
- `master` holds the same HTML plus `img/` and `style/`.

To view the complete site, check out `master` and open `index.html` in a browser (or serve the folder with any static file server, e.g. `python3 -m http.server`).

## Status

Archived early front-end project from 2021, not maintained.
