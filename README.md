cleboundaries
=============

City of Cleveland ward boundaries as of January 1, 2014. 

some of the TODO: 
- find existing city of cleveland ward boundaries (SHP would work)

- obtain census tracts with population inside them from http://www.census.gov/geo/maps-data/data/tiger-data.html
and then figure out how to include in the projects as WNYC did. 

- figure out tooltips. 

Inspired by: 

http://project.wnyc.org/nyc-districting-revised/index.html?lat=40.7370&lon=-73.9220&zoom=12

contents: 

2014wardboundaries-proposed.osm - 
the first public release of 2014 ward boundaries.


2014wardboundaries.osm
- the revised boundaries. 


2014wardboundaries.shp 


boundaries-proposed
- tilemill project that includes the styling of the proposed borders. 
- I used a pgsql (via osm2pgsql). 
Before I made the shapefile, I had to convert the .osm to a postgis-enabled pgsql database.
 You can just use the shapefile instead. 

index.html 
- simple html page using mapbox.js that displays the borders over a mapbox basemap. 

License: 
WTFPL