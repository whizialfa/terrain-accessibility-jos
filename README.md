# School accessibility in Jos

Cost-distance model of school accessibility in Jos, Plateau State. Slope and the road network are the impedance. Travel time is then classed into zones, and the child population is counted inside each zone.

The write-up is `School_Accessibility_Jos.pdf`. The QGIS project is `Terrain Accessibility in Jos.qgz`. The model is `Jos_Terrain_Friction.model3`.

Maps:

- `maps/Integrated Travel Time Surface.png`
- `maps/School Accessibility Zones.png`
- `maps/Undeserved Areas in School Accessibility.png`

These files are not in the repo, because each one is over GitHub's 100 MB limit:

- slope friction and road friction rasters
- the Jos elevation grid
- `Version 2/School_Access_Zones.shp`

The elevation grid is a public DEM. The road layers that are small enough are in the repo (`Jos roads.shp` and related files). Rebuild the surfaces with `Jos_Terrain_Friction.model3`.
