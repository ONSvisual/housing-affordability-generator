# housing-affordability-generator
Script to generate tiles for the revamped housing affordability interactive

Prequistives: mapshaper, gdal, tippecanoe, wget

You'll need to first download the buildings shapefile with MSOA level information attached to it - available here - https://drive.google.com/file/d/1aOyaspIx26gVSXBNzt2e1qKEWGApNTpo/view?usp=sharing

You need a .csv with the house price data required for the map - the fields need to match that used in script and to have the first row as column names. 

Run `sh houseaffordability.sh` to start generating the tiles

There's some test html files in there that will need a server than can run gzip compression e.g. live-server with some middleware
