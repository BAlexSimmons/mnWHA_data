# Data on marine natural World Heritage areas (mnWHAs)
Supplementary tables and data underlying the publication, Kuempel, Simmons &amp; Davey (in review) "The status of current and tentative marine natural World Heritage areas."

# About this data
This data includes summary statistics as well as the spatial boundaries of current mnWHAs and protected areas that are included in the Tentative World Heritage List (tentative mnWHAs) as of January 2020 across the following metrics used in the analysis: marine wilderness, marine ecoregions, pelagic provinces, threatened species ranges, and cumulative human impacts. 

**Supplementary Table 1** presents a summary of all metrics for each current mnWHA (marine wilderness, cumulative human impacts (2013), change in cumulative human impacts (2008-2013), marine ecoregion, pelagic provinces, and threatened species ranges).

**Suppmenentary Table 2** presents a summary of all metrics for each tentative mnWHA (marine wilderness, cumulative human impacts (2013), change in cumulative human impacts (2008-2013), marine ecoregion, pelagic provinces, and threatened species ranges).

**Legend:** because tentative mnWHAs are composed of one or more existing protected areas, we provide a legend that lists the corresponding protected area(s) composing each tentative mnWHA. This is linked to the WDPA_PID field from the World Database on Protected Areas (see data sources) which can be used to match sites between datasets.

**Representation data (tabular):** we provide tables that list, for each current and tentative mnWHA, (1) the marine ecoregion(s) covered, (2) the pelagic province(s) covered, and (3) the threatened species range(s) covered.

**Boundaries data (spatial):** we provide the polygon boundaries of each current and tentative mnWHA included in analyses (Mollweide projection). The polygons have been clipped to exclude any terrestrial areas. Each file has a field identifying the respective current or tentative mnWHA ID for linking to summary datasets.

# Data sources
**Spatial boundaries** of all mnWHAs were obtained from the World Database on Protected Areas ([WDPA](https://www.protectedplanet.net/)). Only protected areas designated as either marine or mixed terrestrial/marine were included, and only those that are either natural or mixed cultural/natural properties. We also excluded mnWHAs with less than 10 pixels of approx. 1 square kilometer resolution. Tentative mnWHA boundaries were estimated based on the description in the Tentative World Heritage List and the corresponding areas in the WDPA.

**Marine wilderness** data was obtained from [Jones et al. (2018)](https://knb.ecoinformatics.org/view/doi:10.5063/F1RR1WFT).

**Ecoregion** data ([The Nature Conservancy 2012](https://data.unep-wcmc.org/datasets/38)) was obtained from the global extent of 232 marine ecoregions (coast and shelf areas) ([Spalding et al. 2007](https://doi.org/10.1641/B570707)) and 37 pelagic provinces (surface waters) ([Spalding et al. 2012](https://doi.org/10.1016/j.ocecoaman.2011.12.016)).

**Threatened species ranges** were obtained from the [IUCN Red List of Threatened Species databases](https://www.iucnredlist.org/resources/grid/spatial-data) of terrestrial and marine mammals, amphibians, reptiles, Chondrichthyes, marine fishes, cone snails, lobsters, sea cucumbers, and freshwater shrimps, crabs, and crayfishes. We exclude any species classified as 'data deficient' or 'least concern' as well as any ranges that are known to be extinct. Subspecies were aggregated at the species level.

**Average human impacts** were estimated using the 2013 map of marine cumulative human impacts (CHI) by [Halpern et al. (2015)](https://knb.ecoinformatics.org/view/doi:10.5063/F1S180FS). Average changes in CHI between 2008 and 2013 were also obtained from Halpern et al. (2015). Climate-based pressures include sea surface temperature, UV radiation, ocean acidification, and sea level rise. Ocean-based stressors include fishing (destructive fishing, non-destructive low bycatch, non-destructive high bycatch, pelagic low bycatch, pelagic high bycatch, and artisanal fishing), shipping routes, invasive species, and ocean pollution. Land-based stressors include population density, night-lights, fertilizer pollution, pesticide pollution, and other inorganic pollution. Data for sea level rise, shipping routes, invasive species, and ocean pollution were not available for 2008 and were excluded from CHI change calculations. Ocean acidification, artisanal fishing, and inorganic pollution were also excluded because they did not differ between 2008 and 2013.

# Authors
Caitlin Kuempel

Blake Alexander Simmons (*Data Manager*)

Madeline Davey
