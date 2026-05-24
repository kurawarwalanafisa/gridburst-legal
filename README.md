# gridpop-legal

Public static site that hosts the **Terms of Service** and **Privacy Policy** for the GridBurst mobile app.

Served via GitHub Pages at `https://<owner>.github.io/gridpop-legal/` (or a custom domain if configured).

## Files

| File | Purpose |
|---|---|
| `index.html` | Landing page with links to Terms and Privacy. |
| `terms.html` | Renders `TERMS.md` client-side via marked.js. |
| `privacy.html` | Renders `PRIVACY.md` client-side via marked.js. |
| `style.css` | Shared dark theme matching the in-app look. |
| `TERMS.md` | Canonical Terms of Service (source of truth — copy from the GridBurst app repo). |
| `PRIVACY.md` | Canonical Privacy Policy (source of truth — copy from the GridBurst app repo). |

## Updating

1. Edit `TERMS.md` and/or `PRIVACY.md` in the **app repo** (`gridpop` / `gridburst`), bumping the `Version` and `Effective Date` fields.
2. Copy them over:
   ```sh
   cp ../gridpop/TERMS.md TERMS.md
   cp ../gridpop/PRIVACY.md PRIVACY.md
   ```
3. Commit and push. GitHub Pages will redeploy automatically.
4. In the app, bump the `TNC_VERSION` constant in `index.html` so existing installs are re-prompted to accept the new version on next launch.

## Deploying to GitHub Pages

1. Create a new **public** repository on GitHub named `gridpop-legal` (or `gridburst-legal` if migrating).
2. From this directory:
   ```sh
   git init
   git add .
   git commit -m "Initial: GridBurst legal site"
   git branch -M main
   git remote add origin git@github.com:<owner>/gridpop-legal.git
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)`** → Save.
4. Wait ~1 minute for the first build, then visit `https://<owner>.github.io/gridpop-legal/`.
5. (Optional) Add a custom domain (e.g., `legal.gridburst.app`) via **Settings → Pages → Custom domain** and a `CNAME` DNS record.

## License

The source code of this site (HTML/CSS) is released under MIT. The legal text in `TERMS.md` and `PRIVACY.md` is the property of the GridBurst publisher and is provided for reference only — do not reuse for another product without legal review.
