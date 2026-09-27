This is my portfolio 

https://bot9315.github.io/

## Deploy on Render (render.com)

The repo includes a `render.yaml` Blueprint, so deploying takes a couple of clicks:

1. Go to <https://dashboard.render.com> and sign in with GitHub.
2. Click **New** → **Blueprint**.
3. Select the **BOT9315.github.io** repository (grant Render access to it if asked).
4. Render reads `render.yaml` and creates the Static Site automatically — no build command, publish directory is the repo root.
5. When the deploy finishes, the site is live at `https://bot9315-portfolio.onrender.com`.

Every push to `main` redeploys the site automatically.

> Alternative without the Blueprint: **New** → **Static Site** → connect this repo → leave **Build Command** empty and set **Publish Directory** to `.`

## Deploy on GitHub Pages

Already live at <https://bot9315.github.io/> — this repo is a GitHub Pages user-site, so the `index.html` on `main` is served as-is.
