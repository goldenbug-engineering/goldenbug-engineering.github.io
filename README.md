# goldenbug-engineering.github.io

The Golden Bug website, served by GitHub Pages at https://goldenbug-engineering.github.io/.

- `index.html`: the home page, with the gold ladybug logo (`logo.png`, 192 px; `favicon.png`, 32 px) beside the name.
- `ribbit-rush/privacy/`: Ribbit Rush's privacy policy, linked from its Google Play listing. **Its source is `docs/privacy-policy.html` in the Ribbit Rush repository**: change it there first, then copy it here (keeping the favicon links this copy adds in its head), and move the effective date whenever what the game collects changes.
- `ribbit-rush/support/`: Ribbit Rush's support page (the listing's website).

Plain static HTML, no build step. `.nojekyll` tells Pages to serve the files as they are.
