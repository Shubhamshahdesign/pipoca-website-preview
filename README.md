# Pipoca Vegan – website preview

Design preview prepared by The Saturn Studio. Not the official Pipoca Vegan website.
Search engines are blocked (`noindex` + `robots.txt`) while this is a preview.

## Publish on GitHub Pages

1. Create a new public repo on GitHub, e.g. `pipoca-preview`.
2. Upload everything in this folder (keep the `images/` folder as is), or from a terminal:

   ```
   git init
   git add .
   git commit -m "Pipoca Vegan preview"
   git branch -M main
   git remote add origin https://github.com/<your-username>/pipoca-preview.git
   git push -u origin main
   ```

3. In the repo go to **Settings → Pages**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute the site is live at `https://<your-username>.github.io/pipoca-preview/`.

## When the client signs off

- Remove the preview bar (`<div class="preview" ...>` near the top of `index.html`).
- Remove the `robots` meta tag and `robots.txt`.
- Add their domain in **Settings → Pages → Custom domain** and point their DNS at GitHub Pages.
