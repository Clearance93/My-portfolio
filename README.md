# clearance93.github.io

My portfolio: **https://clearance93.github.io/My-portfolio/**

A single-page, hand-written site — no framework and no build step. It covers the two products I
have shipped end to end, the way I work, my experience and the stack I use.

## Stack

- Semantic HTML, one page.
- CSS custom properties, Grid and Flexbox; no framework.
- About 100 lines of vanilla JavaScript: mobile menu, scroll reveal, smooth in-page links.
- WebP screenshots and a 1200 × 630 social preview.
- Deployed with GitHub Pages (`.github/workflows/static.yml`).

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The portfolio page |
| `styles.css` | All styling, organised by section |
| `main.js` | Mobile menu, reveal, anchor offset |
| `assets/` | Screenshots, CV and social preview |
| `favicon.svg` | Monogram favicon |

## Local preview

Open `index.html`, or serve the folder:

```bash
npx serve .
```

## Deploying

Push to `main`. The Pages workflow uploads the repository root and publishes it at
`https://clearance93.github.io/My-portfolio/`.

All asset paths are relative, so the site also works from a custom domain or a Netlify drag-and-drop
without changes.

## Editing notes

- Colours and type live in `:root` at the top of `styles.css`.
- Replace `assets/Clearance-Morumudi-CV.pdf` to update the downloadable CV.
- If you replace a screenshot, keep the `width` and `height` attributes in `index.html` in sync.
