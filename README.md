# Pachnę

Personal fragrance tracker: collection, 1–10 ratings, decants vs full bottles,
cost per ml, occasions and a "to test" list.

## Status
- Web prototype: single-file HTML app (`index.html`), no build step.
- Planned: native Android app (Kotlin, Jetpack Compose, Room, offline-first).

## Features
- Fragrance list with rating, brand, type (original / inspired) and source
- Decant vs bottle tracking with cost per ml
- Stats: rating distribution, average rating by brand, originals vs inspired
- Occasions and "to test" wishlist
- JSON backup export (filename includes date and time)

## Data
All data is personal and stays on the device.
Backups are not committed to this repository.

## Run
Open `index.html` in a browser.
