# Lunch Scratch

A small scratch-card lunch picker for colleagues around Kuala Lumpur.

**Live site:** https://lunch.makan-lunch.workers.dev  
**GitHub Pages:** https://chengwq95.github.io/lunch-scratch/

## What it does

Lunch Scratch makes the daily “what should we eat?” decision quick and fun:

- Randomly picks one restaurant from the lunch pool.
- Reveals the choice with a scratch-card interaction that works with a mouse or finger.
- Lets the group redraw when the result does not suit the day.
- Lets anyone add or remove restaurants from the pool directly in the page.
- Starts with a prefilled pool of nearby lunch options.

## How to use

1. Open the site on a phone or desktop browser.
2. Scratch the silver panel to reveal the selected restaurant.
3. Choose **换一张（重抽）** to draw another restaurant.
4. Open **奖池** to see the current lunch pool.
5. Enter a restaurant name and select **加入** to add it. Use the × control beside a name to remove it.

## Data and privacy

The restaurant pool is saved with the browser’s local storage.

- Changes stay on the same browser and device.
- No account, server database, tracking, or map API is used.
- Clearing the site’s browser data restores the default restaurant list.

## Run locally

This is a dependency-free static website.

1. Download or clone this repository.
2. Open `index.html` in any modern browser.

No installation, build command, or server is required.

## GitHub Pages

This repository is published from the `main` branch and the root folder. Because the entry file is named `index.html`, GitHub Pages serves it automatically:

https://chengwq95.github.io/lunch-scratch/

## Project files

- `index.html` — the full Lunch Scratch web app.
- `README.md` — project overview and publishing notes.

## Notes

Restaurant availability, opening hours, and menus can change. Confirm the final choice with the restaurant when needed.
