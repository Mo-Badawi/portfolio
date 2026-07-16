# Badawi — Portfolio

Personal portfolio site for Badawi, QA Engineer based in Nablus, Palestine.

## Structure

```
portfolio/
├── index.html      # Page markup
├── css/
│   └── style.css   # All styles
├── js/
│   └── main.js      # Mobile nav + scroll-reveal animation
├── assets/          # Put images / resume PDF here
└── README.md
```

## Before publishing

Update these in `index.html`:
- `mailto:your-email@example.com` → your real email
- LinkedIn / GitHub links in the Contact section (currently `#` placeholders)

## Deploy on GitHub Pages

1. Create a new repo on GitHub, e.g. `portfolio`.
2. Push these files to the repo root (or to a `docs/` folder — either works):
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source** → select `main` branch, root folder.
4. Your site goes live at `https://<your-username>.github.io/portfolio/` within a minute or two.

## Local preview

Just open `index.html` in a browser, or run a local server:
```bash
python3 -m http.server 8000
```
then visit `http://localhost:8000`.
