# florian-heeb.github.io

Personal homepage of Florian Heeb, served by GitHub Pages at https://florian-heeb.github.io/.
Plain HTML and CSS: no framework, no build step, no cookies, no tracking, no third-party requests.

## Files

| File | What it is |
|---|---|
| `index.html` | The homepage (one page) |
| `style.css` | All styles, light and dark theme |
| `Florian_Heeb_CV.pdf` | CV, compiled from `06_Tenure_Track/LaTeX_CV/CV_Florian_Heeb.tex` |
| `assets/headshot.jpg` | Portrait `Heeb.jpg` (Nov 2024 shoot); backdrop lifted +0.5 EV outside a protected subject mask, subject pixels unchanged |
| `assets/dear-chair-cover.jpg` | Title slide of the Dear Chair explorable |
| `assets/og-image.jpg` | Link-preview image (1200 × 630) for LinkedIn, Slack, etc. |
| `fonts/` | Self-hosted fonts (IBM Plex Sans, Source Serif 4, subsets of IBM Plex Mono and Besley) with their SIL Open Font License texts |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Browser and home-screen icons |

The Dear Chair explorable lives in its own repository (`florian-heeb/dear-chair`) and is served at
https://florian-heeb.github.io/dear-chair/.

## Updating

- **Content:** edit `index.html`, then change "Last updated" in the footer.
- **CV:** recompile the LaTeX CV and copy the PDF over `Florian_Heeb_CV.pdf`. Keep the file name, since links point to it.
- **Publish:** commit and push to `main`. GitHub Pages redeploys within a minute or two.

## Preview locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. (Opening `index.html` directly from disk can block the fonts in some browsers.)
