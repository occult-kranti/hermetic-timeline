# The Hermetic Chronology

A single-page, sourced timeline tracing **Hermetic philosophy, magic, and the occult** — from Babylonian celestial divination and Egyptian *heka*, through the Greek Hermetica and their Arabic transmission, to John Dee, the grimoire tradition, the modern magical orders, and the academic study of esotericism.

Every entry carries an **epistemic label** — *documented*, *disputed*, *debunked*, or *conspiracy* — so well-attested history stays visibly separate from popular myth. The page also includes a tiered resource library (scholarly / journal / web) and an honestly framed section of beginner ceremonial practices.

> **Live site:** `https://<your-username>.github.io/<your-repo-name>/`
> *(fill in once you've deployed — see below)*

## What's in the repo

| File | Purpose |
|------|---------|
| `index.html` | The entire site — self-contained HTML, CSS, and JavaScript. No build step, no dependencies. |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing and serve the file as-is. |
| `README.md` | This file. |

The page loads two web fonts from Google Fonts; everything else is inline, so it works offline too (fonts just fall back to system serifs).

## Deploy it on GitHub Pages

You need a (free) GitHub account. The repository must be **public** for Pages to work on a free plan.

### Option A — Browser only (no command line)

1. On GitHub, click **+ → New repository**. Give it a name (e.g. `hermetic-timeline`), set it **Public**, and create it.
2. On the new repo's page, click **Add file → Upload files**, then drag in `index.html` and `.nojekyll` (and `README.md` if you like). **Commit changes.**
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` and the folder to `/ (root)`, then **Save**.
6. Wait a few minutes, refresh the Pages settings, and your live URL will appear at the top.

### Option B — Git command line

```bash
# in the folder containing index.html, .nojekyll, README.md
git init
git add .
git commit -m "Hermetic Chronology timeline"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

Then do steps 3–6 from Option A to switch Pages on.

### Preview locally first (optional)

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in a browser
```

## Notes & troubleshooting

- **Entry file must be `index.html` at the repo root** — Pages serves that by default.
- If **"Deploy from a branch" is greyed out**, the repo is probably private on a free plan. Make it public under **Settings → General → Change visibility**.
- Site not updating? Pages can take up to ~10 minutes, and browsers cache aggressively — try a hard refresh.
- Custom domain and HTTPS can be configured later under **Settings → Pages**.

## Sources & method

The timeline draws on peer-reviewed scholarship and standard editions (Copenhaver, Hanegraaff, Faivre, van Bladel, Pingree, Rochberg, Betz, Davies, Harkness, and others; full list in the page's Library section). Dates for ancient and medieval texts are scholarly estimates, not fixed points. Conspiracy material — "Illuminati bloodline" / "New World Order" narratives — appears only as an object of analysis, clearly labelled, never as fact.

## License

No license is set yet. If you want others to reuse it, consider adding an [MIT License](https://choosealicense.com/licenses/mit/) for the code, or a [Creative Commons](https://creativecommons.org/choose/) license for the written content.
