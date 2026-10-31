# OSM Editor Kit

Packages that help build interactive web maps and map editors.

The focus is [OpenStreetMap](https://www.openstreetmap.org/): most packages grew out of tools
for viewing, checking and editing OSM data. They are not limited to it, and many are useful in
any app that puts data on a map.

There are two kinds of packages here:

- **Framework-independent packages.** Data, catalogues and logic that work with any tech stack.
- **React packages.** Components and hooks for React apps, mostly built on
  [react-map-gl](https://visgl.github.io/react-map-gl/) and [MapLibre](https://maplibre.org/).

## Where to find the packages

The complete list is the npm organisation
[`@osm-editor-kit`](https://npmx.dev/org/osm-editor-kit).

Nearly all packages have their repository here. One repository can hold several packages:
[osm-editor-kit/street-space-editor](https://github.com/osm-editor-kit/street-space-editor)
contains the Street Space Editor and the packages that grew out of it. The one exception is
`key-value-db-client`, which lives in
[FixMyBerlin/key-value-db](https://github.com/FixMyBerlin/key-value-db). Each package's npm page
links to its source repository and README.
