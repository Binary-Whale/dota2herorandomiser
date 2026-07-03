# Dota 2 Hero Randomizer

A single-page hero randomizer styled after Dota 2's in-game hero selection screen. Filter by attribute, role, and difficulty, then roll for a random hero.

Hero portraits load live from Valve's public Dota 2 CDN, so an internet connection is required when viewing the page.

## Hosting on GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. Add `index.html` from this folder to the root of the repository (or to a `/docs` folder — your choice).
3. Push to GitHub.
4. In the repo, go to **Settings → Pages**.
5. Under **Build and deployment**, set **Source** to "Deploy from a branch".
6. Choose the branch (usually `main`) and the folder (`/root` or `/docs`, matching step 2).
7. Save. GitHub will give you a URL like `https://<username>.github.io/<repo-name>/` within a minute or two.

No build step, dependencies, or server required — it's a single static HTML file.

## Local preview

Just open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
