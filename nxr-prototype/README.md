# NXR — Snowmobile Rental App Prototype

An interactive, clickable prototype of the NXR rental app (UX case study, slides 21–41).
It walks through the full rental journey: browse, book, pay, find the shop, get help, and ride.

**Live demo:** `https://<your-username>.github.io/<repo-name>/`

## Screens

| # | Screen | # | Screen |
|---|--------|---|--------|
| 21 | Explore | 32 | Contact |
| 22 | Search | 33 | Loading |
| 23 | Details | 34 | Route |
| 24 | Dates | 35 | Support |
| 25 | Time | 36 | ProTips |
| 26 | Drivers & vehicles | 37 | Tutorials |
| 28 | Booking | 38 | FAQ |
| 29 | Checkout | 39 | Start rental |
| 30 | Booking successful | 40 | Return vehicle |
| 31 | Rewards | 41 | Trip completed |

## How to use

Tap inside the phone to move through the flow, or jump to any screen with the numbered buttons beside it.
The prototype is a single self-contained `index.html` (images embedded), with no build step or dependencies.

## Publish with GitHub Pages

1. Create a new public repository on GitHub.
2. Upload `index.html`, `README.md` and `.nojekyll` (Add file → Upload files → Commit).
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute, your prototype is live at `https://<your-username>.github.io/<repo-name>/`.

## Design

- **Palette:** navy `#1b2f56`, blue `#6a8dbc`, crimson `#be2852`, magenta `#c05986`, pink `#f38596`, gold accents `#c9a24a` / `#e9cf86`
- **Typefaces:** Playfair Display for titles, Mulish for body text (Google Fonts)
- Light screens for browsing and booking; navy confirmation screens (Success, Rewards, Start, Return, Trip) share one layout so the flow reads as one continuous story.
