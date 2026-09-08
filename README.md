# astroharvest-site

The website for **[AstroHarvest](https://astroharvestgame.com)** — landing page and privacy policy.
Served by GitHub Pages.

Public **only** because GitHub Pages requires it. The game's source lives in a separate private
repository; nothing here but the public web pages, the app icon, a background tile and the
Silkscreen typeface (SIL OFL, licence included).

## Editing

Plain static HTML — no build step. Edit and push; Pages redeploys in a minute or two.

- `index.html` — landing page
- `privacy-policy.html` — **linked from the Google Play listing.** Play requires this URL to
  stay reachable. If it 404s, app updates can be rejected.

## Keeping the privacy policy honest

It currently states that the game collects nothing, which is true today. **The moment analytics,
cloud save, in-app purchases or ads ship, this page and Play's Data safety form must both be
updated in the same release** — a mismatch between them is a common cause of rejected updates.
The file carries HTML comments spelling out what to add for each.
