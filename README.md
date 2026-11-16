# Portfolio site

A single static page (`index.html`) plus your resume PDF. No build step.

## Publish free on GitHub Pages (URL: https://zrfox.github.io)

1. On GitHub, create a **public** repo named exactly `zrfox.github.io`.
2. From this folder:

   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/zrfox/zrfox.github.io.git
   git push -u origin main
   ```

3. In the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)**.
4. After a minute or two, the site is live at https://zrfox.github.io.

## Updating

- Edit `index.html`, commit, push.
- To swap the resume, replace `Zachary_Fox_Resume.pdf` (keep the same name) and push.
