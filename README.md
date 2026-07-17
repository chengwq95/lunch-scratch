# Lunch Scratch

A small scratch-card lunch picker for colleagues around Kuala Lumpur.

**Live site:** https://lunch.makan-lunch.workers.dev

## What it does

Lunch Scratch makes the daily “what should we eat?” decision quick and fun:

- Randomly picks one restaurant from the lunch pool.
- Reveals the choice with a scratch-card interaction that works with a mouse or finger.
- Lets the group redraw when the result does not suit the day.
- Lets anyone add or remove restaurants from the pool directly in the page.
- Includes 14 nearby lunch options by default.

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

## Publish with GitHub Pages

This repository is ready for GitHub Pages because the entry file is named `index.html`.

1. Open **Settings** in this repository.
2. Choose **Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder.
5. Save the settings.

GitHub Pages will publish the site at:

`https://chengwq95.github.io/lunch-scratch/`

## Project files

- `index.html` — the full Lunch Scratch web app.
- `README.md` — project overview and publishing notes.

## Notes

Restaurant availability, opening hours, and menus can change. Confirm the final choice with the restaurant when needed.
