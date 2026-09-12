# ElitsaY.github.io

Personal academic page of Elitsa Yotkova. Plain HTML, no build step.

- `index.html`: the whole site
- `assets/img/profile.jpg`: profile photo (square works best)

## Publish

1. Create a **public** repo on GitHub named exactly `ElitsaY.github.io`.
2. From this folder:

   ```bash
   git init && git add . && git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/ElitsaY/ElitsaY.github.io.git
   git push -u origin main
   ```

3. After a minute or two the site is live at https://elitsay.github.io/.
