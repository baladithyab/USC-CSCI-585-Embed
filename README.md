# USC CSCI 585 — Database Systems (Spring 2023)

Interactive demos of selected homeworks from Yan Liu's CSCI 585.
Spatial queries on a Bay Area photo dataset, plus a YouTube-like
relational schema running on PGlite (real Postgres in the browser).

Embeds via codeseys.io's project-embed pipeline. See `web.codeseys.json`.

## Original source

[baladithyab/USC_CSCI585_Spring23](https://github.com/baladithyab/USC_CSCI585_Spring23)
holds the original SQL + PostGIS + Python — this repo is the
visualization layer.

## Demos

- **HW2 — YouTube SQL Schema**: 7 tables (users, channels, videos,
  comments, etc.) with FK constraints. Six original queries run live
  against a PGlite-WASM Postgres in the browser.
- **HW3 — Bay Area Photo Spatial Queries**: 13 geotagged Bay Area
  photos plotted on a map. Toggle convex hull, 4-nearest-neighbor
  search from a clicked point, density coloring. All client-side
  (turf.js + maplibre-gl).

## License

MIT.
