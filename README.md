# Pratyush Pavan — Portfolio

A single-file, zero-build interactive portfolio. Just `index.html` — no frameworks, no compiling.

## Run it locally
Double-click `index.html`. It opens in your browser. (Needs internet for the Google Fonts.)

## Deploy on GitHub Pages (drag & drop)
1. Create a new repository on GitHub.
   - For a root URL like `https://yourname.github.io`, name the repo exactly **`yourname.github.io`**.
   - Otherwise any name works (e.g. `portfolio`) and you'll get `https://yourname.github.io/portfolio/`.
2. In the repo, click **Add file → Upload files**, then drag in `index.html`. Commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, pick **Deploy from a branch**.
5. Branch: **main**, folder: **/ (root)**. Save.
6. Wait ~1 minute, refresh — your site is live at the URL shown on that page.

## Customize
Everything lives in `index.html`:
- Colors/fonts: the `:root` block at the top of `<style>` (change `--accent`, fonts, etc.).
- Content: edit the text directly in the HTML sections (About, Experience, Skills, Projects, Certifications, Contact).
- The role words that type out: the `roles` array in the `<script>`.

## Tips
- Add a project screenshot by dropping image files in the repo and using `<img>` in a card.
- Want a custom domain? Settings → Pages → Custom domain.
