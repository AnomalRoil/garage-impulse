# Garage Impulse

Hold-to-open Bluetooth remote for a Shelly 1 Gen4 wired to a garage door opener, served as an installable web app on GitHub Pages.

## Install on a phone

- **Android:** open the Pages URL in Chrome, then tap **Install** (or **⋮ > Add to Home screen**).
- **iPhone:** open the Pages URL in Safari, then tap **Share > Add to Home Screen**. Safari has no Web Bluetooth, so the installed app can't reach the Shelly. To control the door, open the URL in [Bluefy](https://apps.apple.com/app/bluefy-web-ble-browser/id1492822055) instead.

## Deploy

Every push to `main` deploys through `.github/workflows/pages.yml`. Bump `VERSION` in `sw.js` on each change so installed apps refresh their cache.
