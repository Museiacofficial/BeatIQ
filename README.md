# BeatIQ

Minimal static starter so the repository can be served as a GitHub Pages site or used as the basis for a deployed web app.

## What I added
- `index.html` — minimal landing page
- `styles.css` — small stylesheet

## Run locally
- Open `index.html` in your browser.
- Or serve with a static server:
  - Python 3: `python -m http.server 8000` and open `http://localhost:8000`
  - npm: `npx serve .`

## Deploy to GitHub Pages
1. Commit and push to the `main` branch.
2. In GitHub repository Settings → Pages, set Source to "main" and folder to "/ (root)".
3. Save. The site should be available at `https://Museiacofficial.github.io/BeatIQ/` after a minute.

## Next steps
- Replace these files with your app build output (React, Vite, Next, etc.).
- Or connect the repository to Vercel/Netlify for automatic builds.

If you want, I can also create a GitHub Action to build and publish a frontend framework (React/Vite) automatically — tell me which framework and I'll add it.