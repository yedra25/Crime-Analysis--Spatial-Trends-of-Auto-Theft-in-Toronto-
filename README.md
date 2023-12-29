# Project Title: Spatial Analysis of Auto Thefts in Toronto

## Overview
The project aims to conduct a spatial analysis of auto thefts in Toronto to identify patterns and locations associated with the crime. Understanding the spatial distribution of auto thefts can help in devising strategies to mitigate and prevent such incidents, ensuring the safety and security of individuals in affected neighborhoods.

## Research Question
Is there a spatial pattern among locational aspects of auto theft larceny in Toronto?

## Spatial Analysis Questions
1. How many auto thefts have been committed within a 500-meter radius of major roads in Toronto?
2. How many auto thefts have occurred on each premise type, and which premise type has the highest occurrence?
3. How many auto thefts have occurred in each neighborhood, and which neighborhood has the highest number of auto thefts?
4. Are there police stations within a kilometer of the neighborhoods with the most auto thefts?

## Site Suitability
The analysis focuses on conducting a buffer collection of auto thefts within a 500-meter radius of major road networks in Toronto. Major roadways are crucial traffic points, providing easy access for criminals to target both residential and commercial premises. Identifying neighborhoods with the highest auto thefts near major roads can assist in targeted awareness and policing efforts.

## Data
### Datasets:
1. **Toronto Auto Thefts:** Contains data on auto thefts from 2014 to the current date, including location type, premise type, date, and geographical coordinates.
2. **Toronto Neighbourhood Boundaries:** Defines specific neighborhood boundaries in Toronto.
3. **Toronto Police Facilities Location:** Shows the locations of all Toronto Police Service facilities.
4. **Toronto Major Roads:** A shapefile of major road networks in Toronto.

### Diversity & Relevance
The diverse datasets include information on auto theft occurrences, neighborhood boundaries, police facility locations, and major road networks. Analyzing these datasets collectively provides insights into the spatial patterns of auto thefts, aiding law enforcement and other services in addressing the issue.

## Metadata
- **Toronto Auto Thefts:** Shapefile & CSV, WGS84 coordinate system.
- **Toronto Neighbourhood Boundaries:** Shapefile, WGS84 coordinate system.
- **Toronto Police Facilities Location:** Shapefile, WGS84 coordinate system.
- **Toronto Major Roads:** Shapefile, WGS84 coordinate system.

## Commands
Commands were used to upload the data into PgAdmin 4 with a spatial reference of SRID: 3857, considering the limitations of the Auto Thefts dataset.

## Analysis
### Query Results:
1. Auto thefts within 500 meters of major roads: 83.4% of total auto thefts.
2. Premise types with the most auto thefts: Outside (52.8%), House (32.0%).
3. Top 5 neighborhoods with the most auto thefts: West Humber-Clairville, York University Heights, Etobicoke City Centre, Milliken, Humber Summit.
4. Police stations within 1 km of neighborhoods with the most auto thefts: Etobicoke City Centre, Humber Summit.

## Conclusion
The spatial analysis revealed significant patterns, emphasizing the correlation between auto thefts, major roads, and the absence of police facilities. Recommendations include allocating resources to patrol major roads and establishing police presence in neighborhoods with high auto theft rates. The insights gained contribute to enhancing Toronto's efforts in combating auto theft through spatial analysis.

## References
1. [Toronto Police Service - Auto Thefts Open Data](https://data.torontopolice.on.ca/datasets/TorontoPS::auto-theft-open-data/explore)
2. [Toronto Neighbourhoods - Social Development, Finance & Administration](https://open.toronto.ca/dataset/neighbourhoods/)
3. [Toronto Police Divisions - Toronto Police Service](https://data.torontopolice.on.ca/datasets/TorontoPS::police-divisions/about)
4. [CanMap RouteLogistics Toronto, city subset - DMTI Spatial](https://mdl.library.utoronto.ca/collections/geospatial-data/canmap-routelogistics-toronto-city-subset)
