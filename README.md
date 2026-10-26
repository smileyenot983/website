# Ramil Khafizov — personal website

A static academic website adapted from [Jon Barron's template](https://github.com/jonbarron/jonbarron.github.io), with responsive semantic HTML and locally hosted Lato fonts. No build step, framework, or JavaScript is required.

## Preview

From this directory:

```sh
python3 -m http.server 8000 --directory dist
```

Open http://localhost:8000. You can also open `dist/index.html` directly.

## Edit

- `dist/index.html`: biography, links, publications, experience, and education.
- `dist/stylesheet.css`: layout, typography, and responsive styling.
- `dist/data/publications.bib`: publication citations.
- `dist/images/`: figures from the author's project pages and repositories.
- `scripts/social-card.html`: editable source for the 1200 × 630 social-sharing preview.
- `.openai/hosting.json`: private Sites deployment identity and static directory.

The page intentionally has no portrait or internship/job-search note. ARGeoSplat is clearly labeled as a submission, separate from accepted publications.

## Sources and credits

Biographical content and experience are based on the supplied CV. Publication details were checked against the linked project pages, arXiv, and CVF. Figures are from [NAMVIS](https://corl-team.github.io/namvis/), [ATATA](https://voyleg.github.io/atata/), [G-CUT3R](https://github.com/smileyenot983/G-CUT3R), and [shortcut_pytorch](https://github.com/smileyenot983/shortcut_pytorch). Lato font files are distributed under the SIL Open Font License; see `dist/fonts/OFL.txt`.

The G-CUT3R reconstruction preview is the depth-guided result from [Figure 1 of the paper](https://arxiv.org/html/2508.11379v2#S1.F1). Reconstruction and ATATA previews are resized and compressed copies of the original results.
