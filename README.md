# Rayhoon Persian Kabob House: Website Redesign Demo

A concept redesign of [rayhoonkabob.com](https://rayhoonkabob.com) for Rayhoon's two New Jersey locations (Parsippany & Morristown).

## Features
- Location switcher (Parsippany / Morristown) that updates phone, map, directions and ordering links
- Live "Open now" status computed in New Jersey time; lunch-special banner appears Mon–Fri 11am–3pm
- Searchable, tabbed menu with vegetarian filter and Farsi dish names
- One-tap ordering sheet (DoorDash, Grubhub, Uber Eats, direct ordering)
- Catering request form (front-end demo, not yet connected to email)
- Mobile action bar (Call / Directions / Order) and Google structured data for both locations

## Run locally
Open `index.html` in a browser, or:
```
python3 -m http.server 8000
```

## Deploy
Static site, no build step. On Vercel: import this repo, Framework Preset **Other**, leave build command empty.

> The page includes `<meta name="robots" content="noindex">` so the demo isn't indexed. Remove it when going live.
