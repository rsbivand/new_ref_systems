# Title "Is here still where it was? Changes in terrestrial reference frames in R spatial packages"


### Primary Topic "Geospatial position data in the R ecosystem"


### Keywords (3 to 5) "Spatial data, coordinate reference systems, terrestrial reference systems, EUREF, NSRS"


## Abstract (up to 250 words)

When we represent or analyse spatial data, the position of observations matters. Where objects of interest are, also in relation to each other, and how position is measured, are referenced through coordinate reference systems (CRS), including units of measurement. Local CRS use arbitrary starting points, while standard CRS rely on tabulated values, for example the axis lengths of an ellipsoid representing the Earth.

The R geospatial cluster of contributed packages are largely built on the foundation of Open Source libraries and ancilliary data, including GDAL, PROJ, and through proj.db, the EPSG tabulations of definitions and values used to represent position. Crucially, the tabulations include coordinate transformations from one CRS to another. 

The Earth's tectonic plates are not static bodies, but have often been treated as as such. Much positional data is taken as defined by the World Geodetic System of 1984 (WGS84), without stating which realisation is applied (WGS84 is a datum ensemble); in North America, NAD83 is often treated like this, and the same applies elsewhere. At present, standards in Europe and North America are being upgraded to accommodate movements in three dimensions of tectonic plates, and their stretching and bending. New standards are entering the EPSG database, so through PROJ and GDAL, enter R workflows. As this happens, the same coordinate transformation may yield different results, depending on the CRS definition and EPSG version. We need to be ready for these changes when they become relevant, and this submission will  show how this may be achieved.




### An indication of whether the submitted topic has been presented at previous conferences

No

### Link to an external resource such as a GitHub repo or technical report.

https://github.com/rsbivand/new_ref_systems


