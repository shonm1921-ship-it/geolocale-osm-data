# GeoLocale OpenStreetMap extracts

Per-city SQLite files of the OpenStreetMap features [GeoLocale](https://geolocale.io) uses to score
neighbourhoods and to show places nearby: shops, food, health, education, transport, parks,
water, major roads, street lamps and a building-count grid. One file per city, published as
release assets; `manifest.json` lists every city with its box, source extract and data date.

**Data © OpenStreetMap contributors, available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).**
These files are a Derivative Database of OpenStreetMap and are offered here under the same
licence. Source extracts: [Geofabrik](https://download.geofabrik.de/). The scripts that build them are public:
[geolocale-osm-build](https://github.com/shonm1921-ship-it/geolocale-osm-build). They are
rebuilt every week by `.github/workflows/weekly.yml`.
