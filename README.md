# elitsay.github.io

Personal academic website, built with plain HTML/CSS (no build step).

## Structure

- `index.html` — page content
- `style.css` — styling
- `assets/img/profile.jpg` — portrait
- `assets/CV_Elitsa_Yotkova.pdf` — CV, linked from the page

## Local preview

```bash
python3 -m http.server 4173
```

Then open http://localhost:4173.

## Deploy to GitHub Pages

1. Create a new **public** GitHub repo named exactly `ElitsaY.github.io` (must match your GitHub username `ElitsaY`).
2. Push this folder to it:

   ```bash
   git remote add origin https://github.com/ElitsaY/ElitsaY.github.io.git
   git branch -M main
   git push -u origin main
   ```
3. In the repo's Settings → Pages, set the source to the `main` branch, root folder (GitHub Pages usually auto-detects this for a `username.github.io` repo).
4. The site will be live at `https://elitsay.github.io/` within a few minutes.

## Updating content

Edit `index.html` directly — publications, news, and experience are plain HTML blocks near the top of the file, no templating involved.
