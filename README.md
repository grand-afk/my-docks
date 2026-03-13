# 🚲 My Docks

A personal mobile-optimised page showing live Santander Cycles bike and dock availability for your favourite London docking stations.

**Live at:** `https://grand-afk.github.io/my-docks/`

---

## Features

- **Live data** — bikes, e-bikes, and free docks per station, refreshed every 3 minutes
- **Colour coding** — green/amber/red at a glance
- **Cycle Here** — opens cycling directions straight to the station (Apple Maps on iOS, Google Maps elsewhere)
- **Search** — find any London docking station by name or street and save it
- **Edit mode** — remove stations or drag to reorder
- **Sync** — export your station list as a JSON file, copy it to clipboard, or import it on another device

---

## Syncing Between Devices

Your saved stations are stored in your browser's localStorage — they don't sync automatically. To move your setup to another device:

1. Tap **⇅ Sync** in the header
2. Tap **⬇ Download config** or **⎘ Copy to clipboard**
3. On the other device, open the page, tap **⇅ Sync**, then either **⬆ Import config** (from file) or paste the JSON and tap **Import pasted config**

---

## Adding to Your iPhone Home Screen

1. Open `https://grand-afk.github.io/my-docks/` in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **Add to Home Screen**
4. Tap **Add**

It will appear as an app icon on your home screen.

---

## Updating the Page

To change station defaults or update the code:

1. Go to [github.com/grand-afk/my-docks](https://github.com/grand-afk/my-docks)
2. Click `index.html` → click the **pencil ✏️** edit icon
3. Make your changes
4. Click **Commit changes**

GitHub Pages will redeploy automatically within ~60 seconds.

---

## Data Source

Live data comes from the [TfL BikePoint API](https://api.tfl.gov.uk/) — open data, no API key required.
