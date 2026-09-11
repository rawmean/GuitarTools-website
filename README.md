# GuitarTools — Website

Marketing website for **GuitarTools** — the complete guitar toolkit for iPhone and Apple Watch (chromatic tuner with reference tones, precision metronome, acoustic string-health diagnostics, and AI technique coach).

## Structure

| File | Purpose |
|---|---|
| `index.html` | Landing page — hero, features, screenshot gallery, Apple Watch section, privacy teaser, support CTA |
| `privacy.html` | Privacy policy (own URL) |
| `support.html` | Support page with FAQ and direct email button |
| `styles.css` | Shared stylesheet (ink + mango design system) |
| `site.webmanifest` | PWA manifest / icon metadata |
| `assets/` | Images, screenshots, app icon, favicons, App Store badge |

## Hosting

Hosted on GitHub Pages (public repo). Push this folder to a repo and enable Pages from the main branch root.

## Before publishing

1. **App Store link** — the download buttons currently link to an App Store *search* page (`https://apps.apple.com/us/search?term=GuitarTools`). Once the app is live, replace every occurrence with the direct link: `https://apps.apple.com/us/app/guitartools/id<APP_ID>`.
2. **Support email** — buttons link to `apps@maadotaa.com` with the subject `need help with GuitarTools`. Update if the address changes.
3. **Fonts** — Google Fonts (Fraunces + Inter) are loaded from the Google Fonts CDN.

## Regenerating assets

Screenshots in `assets/screens/` are web-optimized (780px wide) exports of the full-resolution originals. The app icon in `assets/icons/` was composed from the Icon Composer spec (`icon.json`: gray gradient fill, guitar glyph at 0.8 scale, neutral shadow).
