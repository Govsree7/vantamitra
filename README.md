# VantaMitra PWA

This is the phone-friendly installable web version of VantaMitra.

## What it includes
- Ingredient-based recipe suggestions
- Cooking instructions
- Telugu + English UI content from the prototype
- Installable PWA shell
- Offline caching for the app shell
- Standalone app display on supported browsers

## Important
A service worker and PWA installation normally require the site to be served over HTTPS (or localhost during development). Opening `index.html` directly as a file may let the recipe demo work, but it will not provide full PWA installation.

## Easiest phone setup
1. Put this folder on an HTTPS web host.
2. Open the HTTPS address in Chrome on Android.
3. Use the browser menu and choose "Add to Home screen" or "Install app" when offered.
