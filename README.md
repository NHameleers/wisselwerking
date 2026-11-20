# Sideline Subs

Football substitution tracker for the sideline: drag players between pitch and bench, track playing time per player, keep the score and scorers, and download the match as an Excel file.

It is a single web page that can be installed on a phone as an app and works without a connection.

## Files

- `index.html` – the whole app (layout, styling and logic)
- `manifest.webmanifest` – app name, colours and icons for installing
- `sw.js` – service worker that keeps the app available offline
- `xlsx.full.min.js` – SheetJS 0.18.5, used for the Excel export
- `fonts/` – Barlow and Barlow Condensed (SIL Open Font License)
- `icons/` – app icons

## Data

Everything is stored in the browser of the device that uses the app (localStorage). Nothing is sent to a server.

## Updating

Upload the changed files to this repository. Phones pick up the new version in the background and show it the second time the app is opened while online.
