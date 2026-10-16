# Camper Spot Atlas v1

A single-page map for tracking camper van spots, with private photos, WiFi speed readings and a filterable Speedtest layer.

- Map: Leaflet with CARTO / OpenStreetMap tiles (no API key)
- Place search: OpenStreetMap Nominatim (needs the page to be served over https)
- Data (spots, photos, readings) is stored in your own browser, never uploaded

No build step: `index.html` is the whole app.
