# Rakshith Kunduru — Portfolio

Personal portfolio and CV site for Rakshith Dheer Reddy Kunduru, Data & AI engineer based in Dublin.

**Live site:** https://dheer08.github.io/RakshithDheer/

## What's here

| File | Purpose |
|------|---------|
| `index.html` | The whole site: HTML, CSS and JavaScript in one file, no build step |
| `resume.pdf` | Downloadable CV, linked from the site |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

The hero shows an interactive attention heatmap, a nod to my MSc research on explaining what a Vision Transformer looks at when it classifies faces. The site follows the visitor's light or dark setting and has a manual toggle.

## Hosting on GitHub Pages

1. Put `index.html`, `resume.pdf` and `.nojekyll` at the root of the `main` branch.
2. On GitHub, open the repository's **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute or two the site is live at `https://dheer08.github.io/MyWebsite/`.

## Updating

- **Content:** edit the text in `index.html` directly. Each section has an `id` (`about`, `experience`, `projects`, `skills`, `education`, `contact`).
- **CV:** replace `resume.pdf` with a new file of the same name.
- **Preview locally:** open `index.html` in a browser, or run `python -m http.server` in this folder and visit `http://localhost:8000`.

## License

MIT
