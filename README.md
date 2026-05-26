# NYC Walking Tours

A modernized, mobile-first web app based on the original **New York Times Weekend Explorer** neighborhood audio tours, recorded in 2007.

Live site: **https://etong7.github.io/east-village-tour**

---

## Tours

| Neighborhood | Stops | Audio |
|---|---|---|
| East Village | 12 | ~24 min |
| Hell's Kitchen | 11 | ~21 min |
| Brooklyn Underground | 5 | ~9 min |
| P.T. Barnum's Manhattan | 6 | ~10 min |
| Upper East Side Elite | 10 | ~19 min |

---

## Features

- Original 2007 NYT MP3 audio for every stop
- Written narrative and historical context for each stop
- Then & Now panels comparing 2007 conditions to today
- What to Look For at each location
- Embedded Google Maps for each stop
- Progress tracking across tours
- Mobile-optimized — designed to use while walking

---

## Audio Credit

All audio content is original New York Times Weekend Explorer podcast material, recorded in 2007. This project is a personal, non-commercial preservation and modernization effort.

---

## Stack

- Vanilla HTML/CSS/JS — no framework, no build step
- Hosted on GitHub Pages
- Audio served as static MP3s
- Google Maps embed (no API key required)

---

## To Run Locally

```bash
git clone https://github.com/etong7/east-village-tour
cd east-village-tour
python3 -m http.server 8080
```

Open `localhost:8080` in your browser.

---

## Planned

- Historical photo overlays per stop (NYPL + NYC Municipal Archives)
- Walking time estimates between stops
- GPS proximity alerts
- Offline mode via Service Worker
- Transcripts synced to audio timestamps
