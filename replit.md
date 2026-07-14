# תנ"ך על הדרך — אתר הפודקאסט

## Project Overview

A Hebrew RTL website serving as the home of the "תנ"ך על הדרך" children's Bible podcast.

**Stack:** Plain HTML + CSS (no build step, no dependencies)
**Language:** Hebrew (RTL)
**Server:** Python's built-in HTTP server

## How to Run

The workflow "Start application" serves the site:
```
python3 -m http.server 5000
```

Visit port 5000 in the webview.

## Site Sections

1. **Hero** — Podcast cover art, title, and Spotify CTA
2. **חזון** — Vision / mission text
3. **פרקים** — Episodes (links to Spotify)
4. **יוצרים** — Creators (גלעד בראונשטיין, גדעון קובינסקי, חנה קופיצקי)
5. **תמיכה** — Support / WhatsApp contact

## Key Files

- `index.html` — Full single-page site
- `style.css` — All styles (RTL, responsive, Hebrew font)
- `cover.png` — Podcast cover art (logo)
- `creators.jpg` — Photo of Gilad & Gideon

## User Preferences

- Hebrew UI, RTL layout
- Style: clean, childlike, hopeful, colorful
- Colors: deep blue (#1B3A8B), golden amber (#C4860A), parchment (#FFF8EC)
- WhatsApp contact: 0548183020
- Spotify: https://spotifycreators-web.app.link/e/wt4anJmvA4b
