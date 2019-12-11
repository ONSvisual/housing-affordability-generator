# housing-affordability-generator
Script to generate tiles for the revamped housing affordability interactive

Prequistives: mapshaper, gdal, tippecanoe, wget

You need a .csv with the house price data required for the map - the fields need to match that used in script and to have the first row as column names. 

Run `sh houseaffordability.sh` to start generating the tiles

There's some test html files in there that will need a server than can run gzip compression e.g. live-server with some middleware
