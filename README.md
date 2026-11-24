# MemoPark

The English and Spanish website for [MemoPark on the App Store](https://apps.apple.com/app/id1123786909).

- [English](https://pclemente.github.io/memopark-site/)
- [Español](https://pclemente.github.io/memopark-site/es/)

This is a plain HTML and CSS site. The icon is the app’s own artwork; the garage scene is an original illustration. Both language versions work without JavaScript. To preview, run `python3 -m http.server 8000` in this folder.

Edit the English copy in `index.html`, the Spanish copy in `es/index.html`, and the shared design in `assets/`. Keep the App Store Connect campaign link in the download buttons on both pages.

GitHub Pages serves the root of the `gh-pages` branch. After committing on `main`, run `git push origin main main:gh-pages` to publish the same commit on both branches. The **pages build and deployment** run shows the result.
