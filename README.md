# navitals-brouter-americas

Routing tiles (`.rd5`) for [BRouter](https://github.com/abrensch/brouter), used by the Navitals app
for on-device bicycle routing. They are mirrored from brouter.de's `segments4` so the app never
downloads from brouter.de itself.

The planet is split over three repos, each kept under 5 GB of release assets:

- [navitals-brouter](https://github.com/markettner/navitals-brouter): Europe, W30–E50 from N25 up
- [navitals-brouter-americas](https://github.com/markettner/navitals-brouter-americas): W180–W30
- [navitals-brouter-world](https://github.com/markettner/navitals-brouter-world): everything else (Africa, Asia, Oceania)

Each has one rolling release, `tiles`. Tiles are replaced in place on each monthly update, so
download URLs stay stable. `tiles.json` on navitals-brouter's release lists every tile of all three
with its size, sha256 and URL.

Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, available under
the Open Database License (ODbL). Tiles built by the BRouter project (MIT), brouter.de.
