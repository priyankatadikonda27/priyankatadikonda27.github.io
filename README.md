# Priyanka Tadikonda — Portfolio

Static site: plain HTML, CSS and JS. No build step.

## Preview locally
Double-click `index.html`, or run:
```bash
python3 -m http.server 8000   # then open http://localhost:8000
```

## Deploy free on GitHub Pages
1. On GitHub, create a **public** repo named `priyankatadikonda27.github.io` (leave it empty).
2. In this folder:
```bash
git init
git add .
git commit -m "Portfolio site"
git branch -M main
git remote add origin https://github.com/priyankatadikonda27/priyankatadikonda27.github.io.git
git push -u origin main
```
3. Repo → Settings → Pages → Source: *Deploy from a branch*, Branch: `main` / `(root)` → Save.
4. Live in 1–2 minutes at **https://priyankatadikonda27.github.io**

## Updating
Edit `index.html`, then `git add . && git commit -m "Update" && git push`.

- Add project repo links: replace the GitHub profile URL in each "See code on GitHub" link.
- Add the traffic project's metrics when evaluation is done.
- Swap the photo: replace `assets/priyanka.jpg` (4:5 portrait, ~720×900).
