# When Map Met Blog...

A [Leaflet](https://leafletjs.com/) map-based wrapper for our [travel blog](https://www.schemebasedadventure.com/). Loads blog posts in an iframe when their corresponding markers on the map are clicked.

## Features
- [D3](https://github.com/d3/d3) color scale to visually highlight more recent entries.
- Geodesic lines between adjacent entries (thanks to [Leaflet.Geodesic](https://github.com/henrythasler/Leaflet.Geodesic)).
- Fly to entry-specific zoom level on click.
- Highlight active entry via dark marker outline (thanks to [leaflet-svgicon](https://github.com/iatkin/leaflet-svgicon)).
- Click lines to/from active entry to jump to previous/next entry.
- Manually update entries in .js file separate from index.html.

## License

MIT license.