# Aoshen Huang — academic homepage

A minimal, responsive academic homepage, published at
[1537has.github.io](https://1537has.github.io/).

## Editing

- `index.html`: biography, publications, research interests, and contact links.
- `style.css`: typography, spacing, colors, mobile layout, and print styles.
- `assets/avatar.svg`: the locally hosted cartoon robot avatar and favicon.
- Add publication entries to the `publication-list` in `index.html`.

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

## Avatar credit

The avatar uses [Bottts by Pablo Stanley](https://bottts.com/), via
[DiceBear](https://www.dicebear.com/styles/bottts/), whose style page lists
the artwork as free for personal and commercial use. It is saved locally,
so visitors do not need to contact the avatar service.

Source: `https://api.dicebear.com/10.x/bottts/svg?seed=Aoshen&backgroundColor=eaf2f8&baseColor=90caf9&radius=50`

## Publication sources

Metadata checked on 2026-10-08:

- **Skill-Aware Diffusion**: author order and equal contribution from the
  [paper](https://arxiv.org/html/2601.11266v1); T-ASE 2026 venue information from
  [coauthor Jiaming Chen's homepage](https://jiaming-chen.com/).
  The publisher DOI was not independently available, so the entry links to the
  public preprint and [project](https://sites.google.com/view/sa-diff).
- **VLM-SFD**: author order and DOI from the
  [paper record](https://arxiv.org/abs/2506.13428); the displayed online year follows
  the [University of Manchester record](https://research.manchester.ac.uk/en/publications/vlm-sfd-vlm-assisted-siamese-flow-diffusion-framework-for-dual-ar/),
  which dates online publication to 31 October 2025. Some indexes list the issue
  year as 2026. [Project page](https://sites.google.com/view/vlm-sfd/).

The project pages currently label code as coming soon, so no code-release links
are displayed.
