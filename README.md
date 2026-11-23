# WSET Level 2 Wine Regions Map

An interactive study map of the wine regions, grapes and appellations covered in the WSET Level 2 Award in Wines, with tasting notes from class, exam tips, food pairings and grape profiles.

Open `index.html` through any web server (for example GitHub Pages). It loads `regions.js`, `extras.js`, `terrain.js`, `world.json`, `rivers.json`, `contours.json`, `contours/` and the `relief/` images from the same folder.

Map outlines: Natural Earth (public domain) via the world-atlas package (ISC licence). Shaded relief detail and rivers: Natural Earth (public domain). Height colours and contour lines: NOAA ETOPO 2022 bedrock (public domain), 5 arc-minute grid as packaged in rulke/mainland (MIT). Close-up relief and 100 m contours around the wine areas: Terrain Tiles on AWS Open Data (Mapzen/Linux Foundation; sources include SRTM, GMTED2010 and ETOPO1), zoom 9. All reprojected to match the map. Libraries: d3 and topojson-client (ISC), loaded from jsDelivr.
