# Data Notes

## OSM Rivers and Streams

Source: OpenStreetMap

Extraction method: QuickOSM

Query: `waterway=*`

Study area: Ona River Basin

Downloaded: 13 September 2026

Number of features: 1,435

Geometry: Lines

Important fields: `waterway` (text), `name` (text)

Null values: Present

Coverage: Rivers and streams extracted within the study area

### Data limitation

Some attribute fields contain null values. The `name` field, in particular, may not be populated for all mapped waterways because OpenStreetMap features do not necessarily have names.

---

## OSM Settlements

Source: OpenStreetMap

Extraction method: QuickOSM

Query: `place=*`

Study area: Ona River Basin

Downloaded: 13 September 2026

Number of features: 104

Geometry: Points

Important fields: `place` (text), `GNS_DSG_ST` (text), `alt_name` (text)

Null values: Present

Coverage: Settlement locations extracted within the study area, but coverage is not complete


### Data limitation

The OSM settlement dataset should **not be considered a complete inventory of all settlements within the Ona River Basin**. OpenStreetMap is continuously updated through contributions from different sources and users, and some settlements may not yet be mapped or may have incomplete attribute information.

Therefore, the 104 mapped settlement features represent **identified OSM settlement locations**, rather than the total number of settlements in the study area.

For the flood exposure analysis, the settlement dataset should be used together with the population dataset (e.g., WorldPop) and, where possible, other built-up or settlement information to reduce the effect of incomplete settlement mapping.

---

## General Data Quality Note

The OpenStreetMap datasets used in this project are suitable for spatial analysis, but their completeness and attribute quality may vary. Missing attributes and unmapped features should therefore be considered when interpreting the results.

The settlement layer will primarily be used to identify **mapped settlement locations**, while population exposure will be estimated using the population dataset.
