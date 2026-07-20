# tanhx3.github.io

Published via GitHub Pages at https://tanhx3.github.io

## Structure

- `index.html` — single-file site (HTML + inline CSS/JS, no build step)

## Editing

### Update publications
Each publication is an `<article class="pub">` block in `index.html`. To add paper/code links,
replace the `TODO_*` placeholders inside the `pub-links` div:

```html
<a href="TODO_ARXIV_OR_PDF" target="_blank" rel="noopener">Paper</a>
<a href="TODO_CODE_REPO" target="_blank" rel="noopener">Code</a>
```

### Add social links
In the hero `<nav class="hero-contact">`, uncomment and fill the Scholar/GitHub/X links.

## Deploy
Push to `main` — GitHub Pages serves `index.html` automatically.
