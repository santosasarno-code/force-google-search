# Force Google Search

A lightweight Manifest V3 browser extension for Google Chrome and Microsoft Edge that forces the default search engine to **Google (`google.com`)**.

## Features
- Overrides the browser's default search provider to `https://www.google.com/search?q={searchTerms}`.
- Retains address bar search auto-complete (`suggest_url`).
- Lightweight with zero background scripts or tracking.

## Installation (Developer Mode)

1. Download or clone this repository to your local machine:
   ```bash
   git clone [https://github.com/USERNAME/force-google-search.git](https://github.com/USERNAME/force-google-search.git)

## Manual Installation

1. Open your browser and navigate to the extensions page:

   - Chrome: chrome://extensions

   - Edge: edge://extensions

2. Enable Developer mode (top-right toggle in Chrome, or left sidebar in Edge).

3. Click Load unpacked and select the force-google-search folder.

4. When prompted by the browser to confirm the search settings change, click Keep it / Turn on.

## Compatibility
   - Supported: Windows & macOS (Chrome, Edge, and other Chromium-based browsers).

   - Unsupported: Linux (Chromium restricts chrome_settings_overrides on Linux by design).

## License
MIT License
