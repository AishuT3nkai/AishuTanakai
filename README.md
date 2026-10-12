# Aishu — About Me

A small, responsive personal website built with plain HTML, CSS, and JavaScript.

## Run locally

Open `index.html` in a modern browser. No package manager or build step is required.

## Deploy with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push a commit to `main`, or open **Actions** and run **Deploy static site to GitHub Pages** with **Run workflow**.
4. Wait for the workflow to finish successfully. The public URL will be shown in the workflow's **deploy** job summary.

The workflow publishes the repository root, where `index.html` lives.

## Accessibility notes

- Semantic HTML landmarks and headings.
- Visible keyboard focus.
- Secret-page focus management and browser Back/Forward support.
- Respects `prefers-reduced-motion` for scripted scrolling and CSS transitions.

## Notes

This is a static site; it has no server-side code and does not need environment variables.
