# Aoshen Huang — academic homepage

A minimal, responsive academic homepage, published at
[1537has.github.io](https://1537has.github.io/).

## Editing

- `index.html`: biography, research interests, and contact links.
- `style.css`: typography, spacing, colors, mobile layout, and print styles.
- Add a Publications section at the marked comment in `index.html` when details are available.

The site is plain HTML and CSS. It has no JavaScript, build tools, web fonts,
analytics, or third-party widgets.

## Local preview

From the repository root, run:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

GitHub Pages serves the root of the `main` branch. Changes pushed to `main`
are published by the existing Pages deployment.

## Design references

The layout takes inspiration from the content-first approach of
[Jon Barron's academic website](https://jonbarron.info/) and
[al-folio](https://github.com/alshedivat/al-folio).
The HTML and CSS are written specifically for this site.
