# QGIS Workshop: Mapping prejudice in Nashville

Workshop objectives:
* Understand the historic and contemporary links between structural   racism and its manifestations in the built environment, and the potential of using mapping technologies to explore those relationships  
* Develop a basic understanding of how to use QGIS to visualize spatial data, as well as foundational cartographic design choices 
* Access additional resources to develop independent mapping projects 

Part 1: 
* Content: Racialized uneven development 101
* Tutorial: QGIS foundations & best data management practices 
* Goal: Download & import data 

Part 2:
* Content: Cartography 101
* Tutorial: Visualizing spatial data & basic design principles 
* Goal: Create map & spatial narrative 

## Workshop slides: 

The slides for the workshop can be found [here](https://www.canva.com/design/DAFerwZ2bvE/ZI7wwOpSGka9PszxWtor_w/view?utm_content=DAFerwZ2bvE&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink
).

## Links to example mapping projects: 

* [Mapping prejudice](https://mappingprejudice.umn.edu/)
* [Redlining louisville](https://lojic.maps.arcgis.com/apps/MapSeries/index.html?appid=e4d29907953c4094a17cb9ea8f8f89de)
* [Preserving Chinatowns in the United States](https://storymaps.arcgis.com/stories/3fa093b1c6194409ac979b03a4e77ed6)
* [Chicago million dollar blocks](https://chicagosmilliondollarblocks.com/)
* [LA million dollar hoods](https://milliondollarhoods.pre.ss.ucla.edu/)
* [Interstate highway construction](https://www.nbcnews.com/specials/america-highways-inequality/)
* [Anti-eviction mapping project](https://antievictionmap.com/)
* [Property, Police & Personhood](https://challengeinequality.luskin.ucla.edu/property-police/)
* [Native Land Digital](https://native-land.ca/)
* [Mapping Indigenous LA](https://www.arcgis.com/apps/MapJournal/index.html?appid=a9e370db955a45ba99c52fb31f31f1fc)
* [Native Land Information System (NLIS)](https://nativeland.info/)

Nashville / Tennessee focused:
* [Housing segregation in Nashville](https://storymaps.arcgis.com/stories/050e09fabed0474b9687525fbc4e4c9a)
* [Tennessee's African American Neighborhoods](https://tnlibarchives.maps.arcgis.com/apps/MapSeries/index.html?appid=8dba65584072450ca8928a5f3408373f)
* [Landscape of Liberation](https://tnmap.tn.gov/civilwar/freedmen/)


## Workshop data: 

Within the data folder you'll find the following datasets: 

Demographic data: 
* [Dem2021BG](data/demographics/Dem2021BG.geojson) = GEOJSON containing select demographic data (race, income, education, rental households) for 2021 (ACS 5 yr estimates), at the census block group level

Table Join datasets: 
* [CT2010](data/demographics/tableJoin/CT2010/) = shapefile containing census tract boundaries for 2010
* [nhgis_RaceCT](data/demographics/tableJoin/nhgis_RaceCT.csv) = CSV file containing racial demographic data for 1990-2020, standardized to 2010 census tracts (there is a also a .csvt file that accompnies this file)

If you have any issues with the table join, you can find a file for the joined dataset [here](data/demographics/tableJoin/finalJoin/NHGIS_RaceCT.geojson).

Housing & Evictions data:
* [CodeEnf](data/housing/CodeEnf.csv) = CSV file containing code enforcement violations, with lat and long coordinates
* [EvctRatesBG](data/housing/EvctRatesBG.geojson) = GEOJSON containing eviction rates from 2001 - 2016, at the block group level 
* [Evictions2021](data/housing/Evictions2021.csv) = CSV file containing a random sample of evictions from 2021-2022, with lat and long coordinates
* [HOLC](data/housing/HOLC.geojson) = GEOJSON containing the HOLC (redlining) boundaries 
* [mdha](data/housing/mdha.geojson) = GEOJSON containing locations of MDHA owned properties (and vacant land)
* [subhousing](data/housing/mdha.geojson) = GEOJSON containing locations of subsidized housing

Police data: 
* [policeReports](data/police/policeReports.geojson) = GEOJSON containing reported police incidents for 2020 
* [policeVehStops2022](data/police/PoliceVehStops2022.csv) = CSV file containing police vehicle stops for 2022, with lat and long coordinates 

Extra data:
* [DavidsonCnty](data/extra/DavidsonCnty.geojson) = GEOJSON containing the outline of Davidson County 
* [HighwaysDC](data/extra/HighwaysDC.geojson) = GEOJSON containing highways in Davidson County 
* [MetroParks](data/extra/MetroParks.geojson) = GEOJSON containing Metro Nashville Parks 
* [StreetsDC](data/extra/StreetsDC.geojson) = GEOJSON containing streets in Davidson County   

Infrastructure data (the following and _more_ can be downloaded from Nashville's open data portal): 
* [ADA compliance of pedestrian signals](https://data.nashville.gov/Transportation/Pedestrian-Signal-Inventory-and-ADA-Self-Assessmen/6xet-f7u7)
* [ADA sidewalk inventory](https://data.nashville.gov/Transportation/Sidewalk-Inventory-for-ADA-Self-Assessment/vpxc-b5te)
* [Bike racks](https://data.nashville.gov/Transportation/Bike-Racks-GIS-/3wu7-dwzr)

Note: GEOJSONS are like shapefiles, but are condensed into one file. Thus, they are easier to managage, though you still need to protect your file paths!  

## Additional resources: 

Data sources: 
* [Nashville open data portal](https://data.nashville.gov/) 
* [Census data](https://data.census.gov/)
* [NHGIS historic census data](https://www.nhgis.org/)
* [Natural earth data](https://www.naturalearthdata.com/downloads/) - for your basic shapefiles (like lakes, state boundaries, major cities etc.)
* [Redlining boundaries](https://chesapeake-deij2-chesbay.hub.arcgis.com/documents/holc-redlining-mapping-inequality/explore) 

Tech support: 
* [Download and install QGIS](https://docs.google.com/document/d/1E-CC5uFhqbHIgEhzM1LlcSuYSy4vJfr7VQvFQj_OOhc/edit)
* [Table join instructions](QGISTableJoins_2023.pdf) 
* [Working with csvt files](CSVTfiles.pdf)
* [Converting text attribute values to number](https://mapscaping.com/converting-text-to-numbers-in-qgis/) - when your csvt file fails & you need to change the data formatting 
* [Map projections 101](https://pubs.usgs.gov/gip/70047422/report.pdf) 
* [Working with projections in QGIS](https://docs.qgis.org/3.28/en/docs/user_manual/working_with_projections/working_with_projections.html) 

Design support / inspiration: 
* [Color schemes](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3)
* [Enumeration, normalization & classifcation](https://gistbok.ucgis.org/bok-topics/statistical-mapping-enumeration-normalization-classification)
* Creating a [dot density map](https://youtu.be/TOY_7xKtTcU) with demographic data 

## Workshop experience survey: 

Please let me know your thoughts and feeback on the workshop! 
* [Exit survey link](https://forms.gle/c5VsdFS7HFaHkbto7)
 
--------------- 
Emily Barrett, in partnership with Stacy Curry-Johnson and Natalie Robbins 


 
