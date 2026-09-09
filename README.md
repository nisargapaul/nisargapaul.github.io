# Nisarga Paul's research website

A small, static academic website for [nisargapaul.github.io](https://nisargapaul.github.io/).

## Edit

- `index.html`: biography, contact information, and papers. Copy an existing `<li>` in the paper list to add a paper.
- `assets/style.css`: layout, typography, colors, and mobile styles.
- `assets/nisarga-paul.png`: the supplied portrait. Its circular crop is applied with CSS; the original image is unchanged.

No dependencies, JavaScript, external fonts, analytics, or build tools are required.

## Add the CV

Once the final PDF is supplied, save it as `documents/cv.pdf`. Replace the CV comment in the navigation in `index.html` with:

```html
<a href="documents/cv.pdf">CV</a>
```

The CV link is intentionally absent until the PDF is available.

## Hosting and local preview

The site is published with GitHub Pages from the `main` branch at the repository root, at https://nisargapaul.github.io/.

For a preview available only on this computer, run `python3 -m http.server 8000 --bind 127.0.0.1` from this directory and visit `http://127.0.0.1:8000`.

The `.nojekyll` file allows GitHub Pages to serve the static files directly. Future edits should be previewed locally and published only when Nisarga asks.

## Content sources

The affiliation and email were checked against the [Caltech profile](https://www.pma.caltech.edu/people/nisarga-paul) and [Physical Review Letters contact information](https://journals.aps.org/prl/abstract/10.1103/rpj5-cns6). The introduction follows the author's preferred broad description. The bibliography includes the 27 papers from the author's supplied publication list, with recent publication details checked against arXiv and publisher records on September 7, 2026.

The layout takes inspiration from the academic pages of [Hsin-Yuan Huang](https://hsinyuan-huang.github.io/) and [Tomohiro Soejima](https://tomohiro-soejima.github.io/); the implementation is original.
