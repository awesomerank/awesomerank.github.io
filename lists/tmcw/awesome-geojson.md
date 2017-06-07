<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="tmcw/awesome-geojson">tmcw/awesome-geojson</a> with ranks
</p>
---
# awesome geojson [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

GeoJSON utilities that will make your life easier.

### operations

* [geojson-coords ★11](mapbox/geojson-coords): Extract coordinates from GeoJSON
* [geojson-extent](https://www.npmjs.com/package/geojson-extent): compute the bounding box of geojson features
* [geojson-flatten](https://github.com/tmcw/geojson-flatten): flatten multi geometries into normal geometries
* [geojson-multiply ★1 ⏳1Y](haoliangyu/geojson-multiply):  merge normal geojson features into one multi geometry type feature
* [geojson-js-utils ★317](maxogden/geojson-js-utils): JavaScript helper functions for manipulating GeoJSON
* [geojson-merge ★55](mapbox/geojson-merge): Merge multiple GeoJSON files into one FeatureCollection.
* [geojson-normalize ★16](mapbox/geojson-normalize): normalize any geojson object into a geojson featurecollection
* [geojson-pick](https://www.npmjs.com/package/geojson-pick): remove all but specified properties from features in a geojson featurecollection
* [geojson-random](https://github.com/tmcw/geojson-random): generate random geojson points, lines, and polygons
* [geojson-rewind ★19](mapbox/geojson-rewind): enforce ring winding order
* [geojson-summary ★27](mapbox/geojson-summary): get a plain-english summary of what's in a geojson file
* [point-grouper ★26 ⏳3Y](substack/point-grouper): group geojson points into containing polygons
* [geojson-join](https://github.com/tmcw/geojson-join): join geojson against json, dbf, and csv files
* [simplify-geojson ★74](maxogden/simplify-geojson): apply the ramer-douglas-peucker line simplification to geojson features or feature collections in JS or on the CLI
* [turf ★2691](Turfjs/turf): collection of functions for spatial operations and analysis
* [winnow](https://github.com/dmfenton/winnow): run sql queries against geojson with javascript

### editors & viewers

* [geojson.io](http://geojson.io/): web-based editor, supports many filetype imports & exports, operations, sharing via GitHub
* [umap](http://umap.openstreetmap.fr/en/): web-based editor, supports sharing on-site
* [simple geojson editor](https://google-developers.appspot.com/maps/documentation/utils/geojson/): geojson editor on a google map, by google
* [mapstarter](http://mapstarter.com/): helps generate svg, images, and code from GeoJSON
* [gjv ★43 ⏳1Y](anandthakker/gjv): electron app enables viewing GeoJSON locally and hack on it with turf; works offline
* [GeoJSON editor](https://tomscholz.github.io/geojson-editor/): a modified version of Google's simple geojson editor
* [geojson2image](https://github.com/brycejohnston/geojson2image): library for generating images from GeoJSON
* [dropchop](http://dropchop.io/): browser-based GIS based on Turf.js

### validation

* [geojsonhint ★137](mapbox/geojsonhint): find errors in your geojson files

### services

* [geojsonio-cli ★96](mapbox/geojsonio-cli): send geojson features to geojson.io from your command line
* [geojsonio-extension ★1 ⏳3Y](mapbox/geojsonio-extension): chrome extension for editing github files in geojson.io
* [geojsonlint](http://geojsonlint.com/): REST interface for GeoJSON validation
* [mapshaper](http://mapshaper.org/): Simple interface for simplification and conversion of GeoJSON and TopoJSON
* [koop](https://koopjs.github.io): Server with plugins that recast Esri, GitHub, Socrata and other services as GeoJSON endpoints
* [featureserver ★9](featureserver/featureserver): An open source Esri-Style Feature Server

### conversion

* [csv2geojson ★163](mapbox/csv2geojson): convert CSV to geojson
* [geojson-mapnikify ★20](mapbox/geojson-mapnikify): Transform GeoJSON objects into Mapnik XML stylesheets with embedded GeoJSON data and simplestyle-spec-derived styles.
* [geojson-vt ★590](mapbox/geojson-vt): Slice GeoJSON into vector tiles on the fly in the browser
* [geojson2dsv](https://github.com/tmcw/geojson2dsv): convert geojson to csv and tsv
* [geojson2rtree ★4 ⏳3Y](maxogden/geojson2rtree): generate a static rtree (using terraformer) from a set of geojson features
* [ogr2ogr](http://www.gdal.org/ogr2ogr.html): convert anything to anything
  * [fiona ★337](toblerity/fiona): nice python interface on top of ogr
* [minjur ★44](mapbox/minjur): converts OpenStreetMap data to GeoJSON faster than anything else
* [shp2json ★108 ⏳1Y](substack/shp2json): convert shapefile zip archives to streaming GeoJSON
* [togeojson ★599](mapbox/togeojson): convert gpx & kml to geojson
* [tokml ★67 ⏳1Y](mapbox/tokml): convert geojson to KML
* [topojson ★2857](topojson/topojson): convert GeoJSON to & from TopoJSON, join data from CSV
* [vt-geojson ★38 ⏳1Y](developmentseed/vt-geojson): Extract GeoJSON from Mapbox vector tiles
* [wellknown ★112](mapbox/wellknown): convert wkt to geojson
* [osmtogeojson ★234](tyrasd/osmtogeojson): convert OpenStreetMap data to GeoJSON
* [esri2open ★210 ⏳1Y](project-open-data/esri2open) converts proprietary Esri formats to GeoJSON
* [gtfs2geojson](https://github.com/tmcw/gtfs2geojson): convert GTFS transit data to GeoJSON
* [geoxform](https://github.com/koopjs/geoxform): convert any size stream of geojson into a streaming csv, shapefile or kml, etc.
* [supercluster ★300](mapbox/supercluster): A fast GeoJSON clustering library for browsers and Node.
* [rfc7946-to-d3](https://github.com/tyrasd/rfc7946-to-d3): Converts polygon winding order between rfc7946 and [d3 compatible ★173](d3/d3-geo#d3-geo) conventions.
* [geojson-svgify ★2](juliuste/geojson-svgify): Convert GeoJSON geometry paths to SVG polyline elements.
* [geojson-to-svg-cli ★1](derhuerst/geojson-to-svg-cli): Command line tool to convert GeoJSON to SVG.

### data

* [natural earth](http://www.naturalearthdata.com/): country, province, and geographical data
* [geojson.xyz](http://geojson.xyz/): natural earth data in web-friendly sizes with hotlinking
* [world-atlas ★419](topojson/world-atlas): customizable simplified versions of natural earth data
* [openflights-geojson](https://github.com/tmcw/openflights-geojson): [openflights](http://openflights.org/) airports & airplane routes
* [us-atlas ★509](topojson/us-atlas): geojson & topojson for United States features
* [metro-extracts](https://mapzen.com/data/metro-extracts/): regional OpenStreetMap data as GeoJSON
* [whereonearth-airport ★12 ⏳4Y](straup/whereonearth-airport): outlines of every airport
* [whereonearth-building ★5 ⏳5Y](straup/whereonearth-building): building outlines
* [whereonearth repos](https://github.com/search?q=user%3Astraup+whereonearth): other features output from GeoPlanet by Aaron Straup Cope
* [tgn-geojson ★13 ⏳1Y](straup/tgn-geojson): The Getty Thesaurus of Geographic Names (TGN) As GeoJSON.
* [strava-to-geojsonio ★5 ⏳3Y](taketime/strava-to-geojsonio): export runs & rides from Strava to GeoJSON
* [strava-geojson](https://github.com/tmcw/strava-geojson): export _all_ strava data to geojson, in node & [on the web](http://www.macwright.org/strava-geojson/)

### serialization

* [python-geojson ★259](frewsxcv/python-geojson): serialize geojson to/from python datatypes
* [rgeo-geojson ★110](rgeo/rgeo-geojson): serialize geojson to/from ruby RGeo datatypes
* [rust-geojson ★40](georust/rust-geojson): serialize geojson to/from rust datatypes
* [geojson-jackson ★91](opendatalab-de/geojson-jackson): serialize GeoJSON to and from Java datatypes (based on [Jackson](http://wiki.fasterxml.com/JacksonHome))
* [mapbox-java](https://github.com/mapbox/mapbox-java): serialize GeoJSON to and from Java datatypes (based on [Gson ★8856](google/gson))

### resources

* [RFC 7946 – The GeoJSON Format](https://tools.ietf.org/html/rfc7946): the current GeoJSON standard by IETF
* [GeoJSON.org](http://geojson.org/): the first specification, defining all the rules for GeoJSON structures
* [More than you ever wanted to know about GeoJSON](http://www.macwright.org/2015/03/23/geojson-second-bite.html): a review of the concepts behind the specification in a more narrative format.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/ )

To the extent possible under law, [Tom MacWright](http://www.macwright.org) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="tmcw/awesome-geojson">tmcw/awesome-geojson</a> with ranks
</p>
