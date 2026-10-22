# India Village Explorer

An interactive map that drills down from India to state, district, sub-district and village, with dropdowns,
choropleth colouring, village details and CSV export. It works on desktop and phones.

**Open it:** https://praveen3214.github.io/india-village-explorer/

- **Boundaries:** Survey of India village boundaries. About 34,000 villages, mostly in Arunachal, Meghalaya,
  Nagaland, Mizoram, Ladakh and the hill districts, have no boundary in the source. They are shown as dots at
  their location.
- **Attributes:** Census 2011 Village Directory, so population and amenity figures are from 2011.
- **Basemaps:** © Esri and its data providers.

This repo holds only the generated site (`index.html` + `data/`). It is rebuilt by `build_web.py` from the cleaned GeoParquet files.
