# Path-JEPA — project page

Static, single-file project page for **Path-JEPA (ECCV 2026)**. No build step, no dependencies.

## Deploy to GitHub Pages

**Option A — user/project site**
1. Create a repo, e.g. `path-jepa`.
2. Add `index.html` to the repo root and push.
3. Repo → **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save.
4. Live at `https://<username>.github.io/path-jepa/` in a minute or two.

**Option B — root site**
Name the repo `<username>.github.io` and push `index.html` to root. Live at `https://<username>.github.io/`.

## Before you publish — fill in the placeholders

In `index.html`, replace `href="#"` on the four hero buttons with real URLs:

| Button | Points to |
| --- | --- |
| Paper | PDF (e.g. `paper.pdf` in the repo, or the ECCV proceedings link) |
| arXiv | your arXiv abstract page |
| Code | GitHub repository |
| BibTeX | already anchors to the on-page citation block |

Author links (`<a href="#">` in `.authors`) can point to homepages/Scholar.
Update the BibTeX `booktitle`/pages once the official ECCV entry is out.

## Notes
- Fonts load from Google Fonts (Space Grotesk, Newsreader, JetBrains Mono).
- The hero animation respects `prefers-reduced-motion`.
- To add teaser images/figures, drop them in the repo and reference with `<img>`.
