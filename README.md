# GeoJSON/TopoJSON Austria (2017)
Geo- and TopoJSON files of municipalities, districts and states in Austria, as of January 2017 
(an older version can be found in the folder '2016' - it includes municipalities, districts and states as of June 2016)

The files are based on [Geoland.at/Land Kärnten](https://www.data.gv.at/katalog/dataset/c33d36b0-f184-4f2a-89cc-839ca7fcf88a) and have been modified in several ways:

1. The files contain only two fields:
  * iso (string): the 'Gemeindekennziffer', a number to identify region/state (first digit), district (first three digits) and municipality (whole number) - accordingly the iso in district and state files is only three or one character long
  * name (string): the name of the municipality
2. Fixed several spelling issues with the names
2. Standardised "Sankt" and "St."
3. Changed the 'Gemeindekennziffer' of municipalities in the former district of 'Wien Umgebung', as it was disbanded 2017
4. Simplified to 95%, 99.5% and 99.9% (using [mapshaper.org](http://www.mapshaper.org))
5. Turned into GeoJSON and TopoJSON format
6. Created district and state files for easier use (no more merging if you only need a certain level)
  * The district files don't contain 'Wien Umgebung' any more - if necessary, use the files from 2016

The folder "2017" now contains some special maps:
* district maps with vienna as an enlarged feature, hovering over bavaria
* municipality maps with vienna being divided into districts


CC BY 4.0, Flooh Perlot (https://creativecommons.org/licenses/by/4.0/)

Original file: CC BY 3.0 Geoland Kärnten
