# Geospatial Modelling of Flood Susceptibility and Population Exposure in the Ona River Basin, Southwestern Nigeria

## 1. Research Question

Which settlements and populated areas within the Ona River Basin in Southwestern Nigeria are most susceptible to flooding, and how many people are potentially exposed to these flood-susceptible areas?

## 2. Study Area

Ona River Basin, Southwestern Nigeria

The study focuses on the Ona River Basin and its associated settlements and drainage system, with particular attention to areas within the basin that may be susceptible to flooding and the populations potentially exposed to this hazard.

## 3. Why It Matters

Flooding affects settlements, infrastructure, livelihoods, and public safety within the Ona River Basin. Identifying areas with high flood susceptibility and estimating the population exposed to these areas can help planners, emergency-management agencies, and other relevant authorities prioritize flood-risk reduction, preparedness, and response.

## 4. Data Needed and Data Sources

| Dataset                       | Purpose                                                                                                                                             | Source                                                                                                                    |
| ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Digital Elevation Model (DEM) | Derive elevation, slope, flow accumulation, and other terrain-related flood factors                                                                 | [Copernicus Data Space](https://dataspace.copernicus.eu/)                                                                 |
| River and stream network      | Determine proximity to rivers and support drainage analysis                                                                                         | [OpenStreetMap](https://www.openstreetmap.org/) / [Geofabrik](https://download.geofabrik.de/)                             |
| Rainfall data                 | Represent rainfall conditions that influence flooding                                                                                               | [CHIRPS](https://www.chc.ucsb.edu/data/chirps)                                                                            |
| Land Use/Land Cover (LULC)    | Identify built-up areas, vegetation, bare land, water bodies, and other surface characteristics                                                     | [ESA WorldCover](https://esa-worldcover.org/)                                                                             |
| Soil data                     | Represent soil characteristics affecting infiltration and surface runoff                                                                            | [ISRIC SoilGrids](https://soilgrids.org/)                                                                                 |
| Settlement data           | Identify the location and spatial distribution of settlements and populated places within the Ona River Basin; support settlement exposure analysis | [OpenStreetMap](https://www.openstreetmap.org/) / [Geofabrik](https://download.geofabrik.de/)                             |
| Population data               | Estimate the population exposed to flood-susceptible areas                                                                                          | [WorldPop](https://www.worldpop.org/)                                                                                     |
| Historical flood data         | Provide known flood locations/events for model validation                                                                                           | [NASA Earthdata](https://www.earthdata.nasa.gov/) / [Dartmouth Flood Observatory](https://floodobservatory.colorado.edu/) |

### 5. Derived Variables

Some variables required for the analysis will be derived from the datasets above rather than obtained as separate datasets:

* Elevation
* Slope
* Flow accumulation
* Drainage density
* Distance to rivers/watercourses
* Settlement density or settlement distribution
* Population exposed within flood-susceptible areas

The Ona River Basin boundary will be delineated from the DEM using GIS-based watershed analysis where appropriate.

Settlement data will be used to identify communities and populated locations within the basin and to determine which settlements intersect or fall within areas classified as having moderate, high, or very high flood susceptibility.


## 6. What Will Be Built

The project will produce a GIS-based flood susceptibility map of the Ona River Basin, classifying locations from low to very high flood susceptibility.

The susceptibility map will then be overlaid with population and settlement data to identify populations exposed to flood-susceptible areas. The final outputs will provide spatial information that can support flood-risk planning, preparedness, and decision-making.

## 7. Expected Outputs

Ona River Basin boundary map
Flood-conditioning factor maps
Flood susceptibility map
Settlement exposure map
Population exposure map
Final GIS map suitable for research and planning purposes


