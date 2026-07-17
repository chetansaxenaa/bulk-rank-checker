# Bulk Rank Checker

A single-file, browser-based tool for checking where your domain ranks on Google
for a list of keywords — with proper geo-targeting down to the city level.

## Features

- **Bulk checking** — paste up to 500 keywords, one per line
- **Country + city targeting** — check rankings as Google would show them in a
  specific location, not just a country
- **Smart location detection** — automatically pulls the city/area out of each
  keyword (e.g. "best dentist in Jaipur" is checked from Jaipur automatically)
- **Manual location search** — type any city, town, or village worldwide and
  pick it from live autocomplete suggestions; optionally force that one location
  for every keyword in the batch
- **Configurable check depth** — Top 10, 20, 50, or 100 results
- **Results dashboard** — Top 3 / Top 10 / 11–30 / Not found summary chips,
  sortable and filterable results table
- **Export** — copy results to clipboard (paste straight into Excel/Sheets) or
  download as CSV

## How it works

The tool runs entirely client-side in your browser. It uses:
- **[Serper.dev](https://serper.dev)** to fetch real Google search results (free
  tier: 2,500 searches) — you supply your own API key, which never leaves your
  browser
- **OpenStreetMap / Nominatim** to resolve city and location names for
  geo-targeting

## Getting started

1. Open `index.html` in any browser (or visit the GitHub Pages link)
2. Get a free API key at [serper.dev](https://serper.dev)
3. Enter your domain, target country, and keywords
4. Click **Check rankings**

## Privacy

No data is sent to any server other than Serper.dev (for search results) and
OpenStreetMap (for location lookups). There is no backend, no tracking, and no
storage — everything happens in your browser session.
