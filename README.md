# VM icons for leaflet

## Usage

    var L = require("leaflet");
    var VMIcons = require("vm-leaflet-icons");

    // ...

    L.marker([51.5, -0.09], {icon: VMIcons.company}).addTo(map);
