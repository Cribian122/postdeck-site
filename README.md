# PostDeck site

The public homepage, privacy policy and terms of service for PostDeck.

Live at **https://cribian122.github.io/postdeck-site/**

PostDeck is a Windows desktop app. It cuts stream recordings into short vertical clips and posts them to YouTube, TikTok, Instagram, Facebook and Bluesky. It runs on your own computer and has no server.

## Pages

| File | Page |
|---|---|
| `index.html` | Homepage: what PostDeck does, and how it uses Google and YouTube data |
| `privacy.html` | Privacy policy |
| `terms.html` | Terms of service |
| `tiktok*.txt` | TikTok URL ownership check. Do not delete it. |

Google OAuth review and TikTok app review read these pages. Keep the "Use of Google and YouTube data" section and the policy links on the homepage.

## Build

There is no build step. The site is plain HTML and CSS. GitHub Pages serves the `main` branch root.

The fonts are self-hosted (Inter, `fonts/`), so the pages make no requests to other sites.
