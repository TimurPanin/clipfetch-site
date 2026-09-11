# ClipFetch Landing Page

Static landing page for the **ClipFetch Telegram bot**, built as a lightweight public website with a custom domain.

**Live site:** https://lagoda1337.ru  
**Telegram bot:** https://t.me/clipfetch_O1337_bot

## What the site includes

- Responsive single-page layout
- Direct CTA to the Telegram bot
- Russian-language product explanation and FAQ
- Structured FAQ data with JSON-LD
- Canonical URL and social metadata
- `robots.txt` and `sitemap.xml`
- Privacy policy page
- Custom-domain configuration for GitHub Pages

## Tech stack

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **GitHub Pages**

No frontend framework or build step is required.

## Project structure

```text
clipfetch-site/
├── assets/
│   └── logo.svg
├── CNAME
├── index.html
├── privacy.html
├── robots.txt
├── sitemap.xml
└── README.md
```

## Related project

The desktop companion project is available here:

**[Video Downloader GUI](https://github.com/TimurPanin/video-downloader-gui)** — a Windows-oriented downloader built with Python, Tkinter and yt-dlp.

## Deployment

The repository is configured for GitHub Pages and uses the custom domain stored in `CNAME`:

```text
lagoda1337.ru
```

The site is intentionally kept static so it can be deployed without a backend or build pipeline.
