# Saaho Toolkit

**Small tools. Big momentum.** A thoughtfully designed browser toolkit for quick everyday, developer, image, and writing tasks.

## Run locally

```sh
npm install
npm run dev
```

Create a production build with `npm run build`.

## Publish on GitHub Pages

The workflow in `.github/workflows/pages.yml` builds and deploys the site when code is pushed to `main`. For a first deployment, set the repository's Pages source to **GitHub Actions** under **Settings → Pages**. GitHub Pages then serves the project at `https://prabhaskodela.github.io/Saaho/`.

All 24 included utilities work in the browser. QR codes are generated locally. Image edits, password generation, hashes, and text utilities run on the device; saved tools and theme preference use local storage.

