# new_ref_systems


I am considering submitting a talk/lightning talk/poster on the imminent confusion that will hit us when NAD83 is replaced by modernized NSRS (see ia. https://www.ngs.noaa.gov/datums/newdatums/index.shtml, https://www.esri.com/about/newsroom/arcuser/moving-from-static-spatial-reference-systems-in-2022) in North America, and the ETRS89 standard being considered as a datum ensemble in Europe (see ia. https://evrs.bkg.bund.de/Subsites/EVRS/EN/Results_and_Products/NationalRealizationsETRS89/national_realization.html). This hit PROJ with the updated EPSG database released with PROJ 9.8.0 (thread starting https://lists.osgeo.org/pipermail/proj/2026-March/012026.html). 

The changes are going to affect all geospatial software relying on position whether we like it ot not, even if the changes are single-digit metres or less. So affecting anything linking to GDAL/PROJ, and packages using terra, sf, gdalraster, vapour, gdalcubes.

I would like to ask for help in submitting (by tomorrow evening 14 March) and for some input to a "task force" to try to prepare for oncoming changes. Please tell me not to worry and drop this concern, or consider helping to see how to move forward, including talking about this at useR!.

This readme is based on https://stat.ethz.ch/pipermail/r-sig-geo/2026-March/029601.html and https://fosstodon.org/@rsbivand/116221325701116875.


Abstract submitted 14:52 CET 2026-03-14.


