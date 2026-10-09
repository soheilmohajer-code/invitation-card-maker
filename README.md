# Invitation Card Maker | کارت دعوت‌ساز

Single-file, bilingual (Persian / English) invitation card maker. Pick a design, customize the text and font, and export the card as a PNG photo.

تک‌فایل و دوزبانه (فارسی / انگلیسی). طرح را انتخاب کن، متن و فونت را عوض کن و کارت را به‌صورت عکس PNG ذخیره کن.

## Features

- 18 exclusive designs in 4 categories: romantic, friends, formal, online
- Persian + English UI with automatic language detection (`navigator.language`)
- Title / body font picker (Vazirmatn, Katibeh, Aref Ruqaa, Playfair Display, Dancing Script, Inter, …) + title size slider
- PNG export via html2canvas (scale 3), copy-to-clipboard with fallback
- Dark / light theme, responsive layout, settings saved in `localStorage`
- No build step, no dependencies to install

## Usage

Just open `index.html` in a browser, or serve the folder:

```bash
# any static server, e.g.
npx serve .
# or
python -m http.server
```

Then open the printed local URL.

## GitHub Pages

This repo is Pages-ready: the entry point is `index.html` at the repo root.

1. Push to GitHub (see commands below).
2. Open **Settings → Pages → Deploy from a branch → `main` / root**.
3. Your site will be live at `https://<username>.github.io/invitation-card-maker/`.

## Structure

```text
invitation-card-maker/
├── index.html      # the whole app (markup + styles + script)
├── README.md
└── .gitignore
```

Fonts load from Google Fonts and the PNG export uses the html2canvas CDN, so an internet connection is required for those two features.

## License

Free for personal use. If you reuse the designs, a credit link is appreciated.
