# LA Locations

A community-curated map of the best places to visit across LA County.

## About

LA Locations maps genuinely great places in Los Angeles County: amazing cafes and restaurants, neighborhoods worth exploring, filming locations, cultural landmarks, and everything in between.

Instead of cataloging everything, this project focuses on quality. The standard is simple: Would you recommend this place to a friend? If yes, it belongs here.

## Getting Started

**View the map:** [https://romanparker.com/the-map]

## Contributing

### Add a Location

1. Fork the repository
2. Edit `locations.json` and add your location in this format:

```json
{
"title": "Name of the Place",
"address": "Street address",
"lat": 34.0522,
"lng": -118.2437,
"reason": "Why this place is worth visiting (1-2 sentences)"
}
```
3. Submit a pull request

**Tips:**
- Find coordinates using [Google Maps](https://maps.google.com) or [OpenStreetMap](https://www.openstreetmap.org/)
- Keep reasons to 1-2 sentences
- Check that the location isn't already listed

## Licensing

**Map Data:** Licensed under the [Open Database License (ODbL) v1.0](https://opendatacommons.org/licenses/odbl/1-0/). Incorporates data from [OpenStreetMap](https://www.openstreetmap.org/). Attribution: © OpenStreetMap contributors.

**Acknowledgements & Data Sources**

This project utilizes geospatial boundary data provided by the City of Los Angeles:

* **Neighborhood Boundaries**: Derived from the [LA Times Neighborhood Boundaries dataset](https://lacity.org) provided via the [Los Angeles GeoHub](https://geohub.lacity.org/).
* **Original Creator**: Los Angeles Times Mapping L.A. Project.
* **License**: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org).
* *Note: The original dataset was modified using Mapshaper to remove attribute properties and reduce coordinate numerical precision for map performance optimizations.*

**Code:** Licensed under the MIT License.
