# Mukilan — Portfolio

Ready to publish. Folder contains:
- `index.html` — the site
- `Mukilan-Resume.pdf` — résumé (linked from the hero "View résumé" button)
- `assets/certificates/` — all 8 certificate images, wired to the "Certificates" section

## Publish with GitHub Pages

1. Go to your repo: https://github.com/Mukilan029/Portfolio
2. If it already has files, delete/replace them with the contents of this zip (keep the same names/folders — the HTML depends on exact filenames).
3. Upload everything in this folder to the **root** of the repo (drag-and-drop on the GitHub web UI works, or use git — see below).
4. In the repo: **Settings → Pages**.
5. Under "Build and deployment" → Source, choose **Deploy from a branch**.
6. Branch: `main` (or `master`), folder: `/ (root)` → Save.
7. Wait ~1 minute, then your site is live at `https://mukilan029.github.io/Portfolio/`.

## Publish with git (command line)

```bash
git clone https://github.com/Mukilan029/Portfolio.git
cd Portfolio
# copy in index.html, Mukilan-Resume.pdf, and the assets/ folder from this zip
git add .
git commit -m "Update portfolio site"
git push
```

Then enable Pages as in step 4 above (only needed once).
