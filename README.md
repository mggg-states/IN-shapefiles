# Indiana Election Shapefiles
This data was processed by members of the MGGG Redistricting Lab and student research assistant, Rachel Herman.

## Sources
The 2016 precinct boundary shapefile was obtained by contacting the Indiana Secretary of State Election Division. The 2016 election data was downloaded from MIT Election and Data Science Lab, except for attorney general results for Hancock County, Jefferson County, and Madison County. Hancock County election results are from a contact in the County Clerk's Election Department, Jefferson County results are from a contact in the County Clerk's Office of Voter Registration, and Madison County Results are from the county's [Election Board](https://www.madisoncounty.in.gov/assets/precinct-report-------madison-county2016.pdf).

The 2010 Decennial Census block shapefile and demographic data were downloaded from the [National Historic GIS](https://data2.nhgis.org/main#).


## Processing
This shapefile required minimal processing. No digitizing, merging, or splitting of precincts was required. Demographic data were aggregated from the block level using MGGG’s geospatial toolkit.

## Metadata
* `STATE`: State
* `STATEFP`: State FIPS code
* `COUNTYFP`: County FIPS code
* `Precinct`: Precinct name
*	`PRES16D`: Number of votes for 2016 Democratic presidential candidate
*	`PRES16R`: Number of votes for 2016 Republican presidential candidate
*	`SEN16D`: Number of votes for 2016 Democratic senate candidate
* `SEN16R`: Number of votes for 2016 Republican senate candidate
* `SEN16L`: Number of votes for 2016 Libertarian senate candidate
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
* `CD`: Congressional district
* `HDIST`: State House district
* `SEND`: State Senate district

## Projection
This shapefile uses a NAD83/Indiana East (ft) projection (EPSG:2965).

## Rating
We give the shapefile an A- rating. Precinct data were obtained from the state government and election results data required only minor corrections in three counties to reduce discrepancies. Discrepancies from state-reported totals are at most 0.1%.
