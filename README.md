# An Bhean-Fhlâneur — project website (draft v1)

A one-page static site: dark title-card look, teal accent, ripple-map motif.
No cookies, no trackers, no dependencies — just `index.html` + `styles.css`.

## Files

- `index.html` — the page
- `styles.css` — all styling

## Publish on GitHub Pages (one-time)

1. Sign up at **github.com** (free plan is fine).
2. Click **+** (top right) → **New repository**:
   - Name: `an-bhean-fhlaneur-site` (any name works — this only affects the temporary URL)
   - Set to **Public**
   - Tick **Add a README**
   - **Create repository**
3. On the repo page: **Add file → Upload files** → drag in `index.html` and `styles.css` → **Commit changes**.
4. **Settings → Pages** (left sidebar) → under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)** → **Save**
5. Wait 1–2 minutes. The site is live at:
   `https://YOUR-USERNAME.github.io/an-bhean-fhlaneur-site/`

## Before launch — replace the placeholder links

Search the files for `TODO`. Five placeholders:

| Where | What to swap in |
|---|---|
| Hero "Support the film" + Support section | idonate crowdfunder URL (after idonate confirms eligibility) |
| Hero "Read the journal" + Journal card | Substack URL |
| Hero "Take part" + "Open the questionnaire" | Tally questionnaire URL |
| Hero logline | Final one-pager logline |

## Later

- **Custom domain** (e.g. `anbheanfhlaneur.com`, ~€12/yr): buy it, then in
  repo **Settings → Pages → Custom domain**, and add a `CNAME` file — GitHub
  walks you through it.
- **Updates from Vibe**: connect the GitHub connector in Vibe and the site can
  be edited by asking in chat — commits push directly and GitHub Pages
  redeploys automatically.

## Notes

- Accessibility: skip link, keyboard focus states, reduced-motion support and
  AA contrast are built in — keep them for the casting-call audience.
- The site never uses the internal shorthand "ABF" — external title only.
