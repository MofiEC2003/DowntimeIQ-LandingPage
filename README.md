# DowntimeIQ Landing

Single-file landing page for DowntimeIQ.

## Quick publish to GitHub Pages (UI)

1. Create a new repository on GitHub (e.g., `downtimeiq-site`).
2. Upload **index.html** to the root of the repo (drag & drop).
3. Go to **Settings → Pages**.
4. In **Source**, choose **Deploy from a branch**.
5. Select **Branch: `main`**, **Folder: `/ (root)`**, then **Save**.
6. Wait ~1–2 minutes. Your site will be live at:  
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Quick publish (Git commands)

```bash
git init
git add .
git commit -m "Initial commit: DowntimeIQ landing"
git branch -M main
git remote add origin https://github.com/<tu-usuario>/<repo>.git
git push -u origin main
```

Activa GitHub Pages: **Settings → Pages → Deploy from a branch → main / (root)**.
