# QGIS Workshop: Mapping prejudice in Nashville

Workshop objectives:
* Understand the historic and contemporary links between structural   racism and its manifestations in the built environment, and the potential of using mapping technologies to explore those relationships  
* Develop a basic understanding of how to use QGIS to visualize spatial data, as well as foundational cartographic design choices 
* Access additional resources to develop independent mapping projects 

Part 1: 
* Racialized geographies 101
* Tutorial: QGIS foundations & best data management practices 
* Goal: Download & import data 

Part 2:
* Cartography 101
* Tutorial: Visualizing spatial data & basic design principles 
* Goal: Create map & spatial narrative 

## Links to example mapping projects: 

* [Mapping prejudice](https://mappingprejudice.umn.edu/)
* [Redlining louisville](https://lojic.maps.arcgis.com/apps/MapSeries/index.html?appid=e4d29907953c4094a17cb9ea8f8f89de)
* [Preserving Chinatowns in the United States](https://storymaps.arcgis.com/stories/3fa093b1c6194409ac979b03a4e77ed6)
* [Chicago million dollar blocks](https://chicagosmilliondollarblocks.com/)
* [LA million dollar hoods](https://milliondollarhoods.pre.ss.ucla.edu/)
* [Interstate highway construction](https://www.nbcnews.com/specials/america-highways-inequality/)
* [Anti-eviction mapping project](https://antievictionmap.com/)
* [UCLA Luskin Institute of Inequality and Democracy](https://challengeinequality.luskin.ucla.edu/property-police/)
* [Native Land Digital](https://native-land.ca/)
* [Mapping Indigenous LA](https://www.arcgis.com/apps/MapJournal/index.html?appid=a9e370db955a45ba99c52fb31f31f1fc)
* [Native Land Information System (NLIS)](https://nativeland.info/)

Nashville / Tennessee focused:
* [Housing segregation in Nashville](https://storymaps.arcgis.com/stories/050e09fabed0474b9687525fbc4e4c9a)
* [Tennessee's African American Neighborhoods](https://tnlibarchives.maps.arcgis.com/apps/MapSeries/index.html?appid=8dba65584072450ca8928a5f3408373f)
* [Landscape of Liberation](https://tnmap.tn.gov/civilwar/freedmen/)


## Workshop slides: 

The slides for the workshop can be found [here](https://www.canva.com/design/DAFerwZ2bvE/ZI7wwOpSGka9PszxWtor_w/view?utm_content=DAFerwZ2bvE&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink
).

## Workshop data: 

Within the data folder you'll find the following datasets: 

Demographic data: 
* [Dem2021BG](data/demographics/Dem2021BG.geojson) = GEOJSON containing select demographic data (race, income, education, rental households) for 2021 (ACS 5 yr estimates), at the census block group level
Table Join datasets: 
* [CT2010](data/demographics/tableJoin/CT2010/) = shapefile containing census tract boundaries for 2010
* [nhgis_RaceCT](data/demographics/tableJoin/nhgis_RaceCT.csv) = CSV file containing racial demographic data for 1990-2020, standardized to 2010 census tracts (there is a also a .csvt file that accompnies this file)

Housing & Evictions data:
* [CodeEnf](data/housing/CodeEnf.csv) = CSV file containing code enforcement violations, with lat and long coordinates
* [EvctRatesBG](data/housing/EvctRatesBG.geojson) = GEOJSON containing eviction rates from 2001 - 2016, at the block group level 
* [Evictions2021](data/housing/Evictions2021.csv) = CSV file containing a random sample of evictions from 2021-2022, with lat and long coordinates
* [HOLC](data/housing/HOLC.geojson) = GEOJSON containing the HOLC (redlining) boundaries 
* [mdha](data/housing/mdha.geojson) = GEOJSON containing locations of MDHA owned properties (and vacant land)
* [subhousing](data/housing/mdha.geojson) = GEOJSON containing locations of subsidized housing

Police data: 
* [policeReports](data/police/policeReports.geojson) = GEOJSON containing reported police incidents 2020 
* [policeVehStops2022](data/police/PoliceVehStops2022.csv) = CSV file containing police vehicle stops for 2022, with lat and long coordinates 

Extra data:
* [DavidsonCnty](data/extra/DavidsonCnty.geojson) = GEOJSON containing the outline of Davidson County 
* [HighwaysDC](data/extra/HighwaysDC.geojson) = GEOJSON containing highways 
* [MetroParks](data/extra/MetroParks.geojson) = GEOJSON containing Metro Parks 
* [StreetsDC](data/extra/StreetsDC.geojson) = GEOJSON containing streets  

Note: GEOJSONS are like shapefiles, but are condensed into one file. Thus, they are easier to managage, though you still need to protect your file paths!  

## Additional resources: 

Data sources: 
* [Nashville open data portal](https://data.nashville.gov/)
* [Census data](https://data.census.gov/)
* [NHGIS historic census data](https://www.nhgis.org/)
* [Natural earth data](https://www.naturalearthdata.com/)
* [Redlining boundaries](https://chesapeake-deij2-chesbay.hub.arcgis.com/documents/holc-redlining-mapping-inequality/explore)

Tech support: 
* [Download and install QGIS](https://docs.google.com/document/d/1E-CC5uFhqbHIgEhzM1LlcSuYSy4vJfr7VQvFQj_OOhc/edit)
* [Table join instructions](QGISTableJoins_2023.pdf) 
* [Converting text attribute values to number](https://mapscaping.com/converting-text-to-numbers-in-qgis/)
* Creating a [dot density map](https://youtu.be/TOY_7xKtTcU) with demographic data 

Design support / inspiration: 
* [Color schemes](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3)
 
--------------- 
Emily Barrett, in partnership with Stacy Curry-Johnson and Natalie Robbins 


 
