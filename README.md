# Portfolio — AI · ML · Immersive Tech

Static portfolio site ready for [GitHub Pages](https://pages.github.com/). No build step: open `index.html` locally or publish the repo root.

## Publish on GitHub Pages

1. Create a new repository on GitHub and push this folder (or make it the repo root).
2. In the repo: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **main** (or **master**) and folder **/ (root)**, then save.

Your site will be available at `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` if the repo is named `<username>.github.io`).

## Customize

- **Identity & copy:** Edit `index.html` — hero, about, projects, teaching, stack, and contact sections.
- **Profile photo:** Replace `assets/profile.svg` with your own image (e.g. `assets/profile.jpg`) and update the `src` in the hero `<img>`.
- **Clients strip & section:** Sample company names are placeholders—edit or remove before publishing.
- **CV:** Place your résumé PDF at `assets/cv.pdf` (or change every `href="assets/cv.pdf"` in `index.html` to match your filename).
- **Email & links:** Update every `mailto:` address and GitHub / LinkedIn URLs in `index.html`.
- **Look:** Adjust colors and fonts in `css/styles.css` under `:root` variables.

## Local preview

Open `index.html` in a browser, or from this directory run a static server, for example:

```bash
npx --yes serve .
```

Then visit the URL shown in the terminal (often `http://localhost:3000`).
