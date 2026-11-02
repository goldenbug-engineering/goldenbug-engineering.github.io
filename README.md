# goldenbug-engineering.github.io

The Golden Bug Games website, served by GitHub Pages at https://goldenbug-engineering.github.io/.

- `index.html`: the home page: the gold ladybug logo (`logo.png`, 192 px; `favicon.png`, 32 px), the name and tagline, and a card per game (Ribbit Rush's uses `ribbit-rush/feature.png`, its store feature graphic). No web fonts or outside requests. Every page's look is in `site.css`.
- `ribbit-rush/privacy/`: Ribbit Rush's privacy policy, linked from its Google Play listing. **Its source is `docs/privacy-policy.html` in the Ribbit Rush repository**: change it there first, then copy it here (only the text between its `<main>` tags; this copy wraps it in the site's head, home link, `<article class="page">` and footer, and takes its look from `site.css`), and move the effective date whenever what the game collects changes.
- `ribbit-rush/support/`: Ribbit Rush's support page (the listing's website).

Plain static HTML, no build step. `.nojekyll` tells Pages to serve the files as they are.
