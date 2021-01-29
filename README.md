# Indiana Election Shapefiles
This shapefile was obtained from the Delaware FirstMap Data website and processed by members of the Metric Geometry and Gerrymandering Group (MGGG).

## Sources
The Indiana prescinct shapefile was obtained from [Delaware FirstMap Data](http://opendata.firstmap.delaware.gov/datasets/delaware-election-boundaries), a GIS service of the State of Delaware. Election data come from the [Delaware Department of Elections](https://elections.delaware.gov/index.shtml). 

2010 Decennial Census demographic data were downloaded from the [Census API](https://api.census.gov/data/2010/dec/sf1). The 2010 census block shapefile for Indiana was downloaded from the US Census Bureau’s [TIGER/Line Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-line-file.html).


## Processing
Some very limited merging of precincts in the tabular election data was necessary to join to the precinct shapefile. Data from three countywide precincts that reported absentee votes were disaggregated by voting age population using MGGG’s proration software. Demographic data was aggregated from the block level using MGGG’s proration software. State legislative district IDs were also assigned to precincts using this package.


## Metadata
* `EDRD_2012`: Precinct name
* `POPULATION`: State-reported population
* `District_1`: Precinct name
*	`PRES16D`: Number of votes for 2016 Democratic presidential candidate
*	`PRES16R`: Number of votes for 2016 Republican presidential candidate
*	`SEN16D`: Number of votes for 2016 Democratic senate candidate
* `SEN16R`: Number of votes for 2016 Republican senate candidate
* `AG16D`: Number of votes for 2016 Democratic attorney general candidate
*	`AG16R`: Number of votes for 2016 Republican attorney general candidate
*	`GOV16D`: Number of votes for 2016 Democratic gubernatorial candidate
*	`GOV16R`: Number of votes for 2016 Republican gubernatorial candidate
* `TOTPOP`: Total population from 2010 Decennial Census
* `NH_WHITE`: White, non-hispanic, population from 2010 Decennial Census
* `NH_BLACK`: Black, non-hispanic, population from 2010 Decennial Census
* `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population from 2010 Decennial Census
* `NH_ASIAN`: Asian, non-hispanic, population from 2010 Decennial Census
* `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population from 2010 Decennial Census
* `NH_OTHER`: Other race, non-hispanic, population from 2010 Decennial Census
* `NH_2MORE`: Two or more races, non-hispanic, population from 2010 Decennial Census
* `HISP`: Hispanic population from 2010 Decennial Census
* `H_WHITE`: White, hispanic, population from 2010 Decennial Census
* `H_BLACK`: Black, hispanic, population from 2010 Decennial Census
* `H_AMIN`: American Indian and Alaska Native, hispanic, population from 2010 Decennial Census
* `H_ASIAN`: Asian, hispanic, population from 2010 Decennial Census
* `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population from 2010 Decennial Census
* `H_OTHER`: Other race, hispanic, population from 2010 Decennial Census
* `H_2MORE`: Two or more races, hispanic, population from 2010 Decennial Census
* `VAP`: Total voting age population from 2010 Decennial Census
* `HVAP`: Hispanic voting age population from 2010 Decennial Census
* `WVAP`: White, non-hispanic, voting age population from 2010 Decennial Census
* `BVAP`: Black, non-hispanic, voting age population from 2010 Decennial Census
* `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population from 2010 Decennial Census
* `ASIANVAP`: Asian, non-hispanic, voting age population from 2010 Decennial Census
* `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population from 2010 Decennial Census
* `OTHERVAP`: Other race, non-hispanic, voting age population from 2010 Decennial Census
* `2MOREVAP`: Two or more races, non-hispanic, voting age population from 2010 Decennial Census
* `HDIST`: State House district
* `SEND`: State Senate district

## Projection
This shapefile uses a NAD83/Indiana East (ft) projection (ESPG:2965).

## Rating
We give these shapefiles an A rating. All data was obtained from the state government and was processed by MGGG staff.
