# Van Spots

A single-page map for tracking camper van spots, with private photos, WiFi speed readings and a filterable Speedtest layer.

- `index.html`: Google Maps version (Maps JavaScript API and Places API (New)). On first load the page asks for your API key and keeps it in your browser only; it is never stored in the code.
- `osm.html`: OpenStreetMap / Leaflet version, no key needed (backup).

Restrict the Google key to this site's address (HTTP referrers) in Google Cloud.

Data (spots, photos, readings) is stored in your own browser, never uploaded. No build step.
