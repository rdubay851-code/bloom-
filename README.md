# Bloom

A calming, responsive multi-page wellbeing website for difficult or lonely moments.

## What's new
- Persistent mood switcher: **Soft Light**, **Night Blue**, **Morning Mist**.
- Mood preference is saved in `localStorage` and restored automatically.
- Dynamic atmospheric background changes with the selected mood.
- Back button on every page; it uses browser history and falls back to Home.
- New **Poetry** page with several original short poems, shuffle and copy controls.
- Expanded Home page with more destinations and gentle interactive elements.
- Night mode adds subtle stars and a cooler ambient palette.
- Future activity chips can be selected interactively.

## Run locally

```bash
python -m http.server 8080
```

Open `http://localhost:8080`.

Everything is client-side. The journal is stored locally in the browser with `localStorage` and is not uploaded by this project.
