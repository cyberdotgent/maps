# Maps

A simple Bootstrap 5 + Leaflet map/search app that works offline at runtime.

## Runtime expectations

- Static tiles are served from `/tiles/{z}/{x}/{y}.png`
- Nominatim is available on the same domain under `/api/search.php` and `/api/reverse.php`
- Third-party front-end libraries are vendored locally under `assets/vendor/`

## Run

Serve the repository as a static site and open `index.html`.
