# 🚲 My Docks

A personal mobile-optimised page showing live Santander Cycles bike and dock availability for your favourite London docking stations.

**Live at:** `https://grand-afk.github.io/my-docks/`

---

## Features

- **Live data** — bikes, e-bikes, and free docks per station, refreshed every 3 minutes
- **Colour coding** — green/amber/red at a glance
- **Cycle Here** — opens cycling directions straight to the station (Apple Maps on iOS, Google Maps elsewhere)
- **📍 Nearby** — finds the 10 closest docking stations to your current location
- **🔍 Search** — find any London docking station by name or street and save it
- **✏️ Edit mode** — remove stations or drag to reorder
- **⇅ Sync** — export your station list as a JSON file, copy to clipboard, or import on another device
- **No defaults** — starts blank; you build your own list

---

## Getting Started

On first open you'll see a welcome screen with two options:

- **Find Nearby Stations** — allows location access and shows the 10 closest stations with live counts
- **Search by Name** — search by street or station name

Tap **＋ Save** on any result to add it to your list.

---

## Nearby Stations

Tap **📍 Nearby** in the header at any time to find the 10 closest stations to where you currently are. Each result shows live bike, e-bike, and free dock counts along with the distance from you.

---

## Syncing Between Devices

Your saved stations are stored in your browser's localStorage — they don't sync automatically. To move your setup to another device:

1. Tap **⇅ Sync** in the header
2. Tap **⬇ Download config** or **⎘ Copy to clipboard**
3. On the other device, open the page, tap **⇅ Sync**, then either **⬆ Import config** (from file) or paste the JSON and tap **Import pasted config**

---

## Colour Guide

| Colour | Meaning |
|--------|---------|
| 🟢 Green | Plenty of bikes / docks free |
| 🟡 Amber | 3 or fewer bikes remaining |
| 🔴 Red | No bikes / no free docks |
| 🟣 Purple | E-bikes available |
| 🔵 Blue | Free docks |

---

## Adding to Your iPhone Home Screen

1. Open `https://grand-afk.github.io/my-docks/` in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

It will appear as an app icon on your home screen.

---

## Updating the Page

1. Go to [github.com/grand-afk/my-docks](https://github.com/grand-afk/my-docks)
2. Click `index.html` → click the **pencil ✏️** edit icon
3. Make your changes
4. Click **Commit changes**

GitHub Pages redeploys automatically within ~60 seconds.

---

## Data Source

Live data comes from the [TfL BikePoint API](https://api.tfl.gov.uk/) — open data, no API key required.
