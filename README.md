# Static Site – Quick Deploy

This folder is ready for one-click/static hosting on **Vercel**, **Netlify**, or **GitHub Pages**.

## Vercel (fastest)
1. Go to https://vercel.com/new
2. Drag & drop this folder, or import from GitHub.
3. Accept defaults. Your public URL is created instantly.
4. (Optional) Use `vercel` CLI: `npm i -g vercel && vercel`

## Netlify (drop-in)
1. Go to https://app.netlify.com/drop
2. Drag & drop this folder. Netlify creates a live URL.

## GitHub Pages
1. Create a repo and push the contents of this folder.
2. In repo Settings → Pages, choose "Deploy from a branch" and select `main` and `/ (root)`.
3. Your site will be live at `https://<username>.github.io/<repo>/`.

Files included:
- `index.html` – your page
- `404.html` – fallback page
- `vercel.json` – Vercel config
- `netlify.toml` – Netlify config
