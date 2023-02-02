# Data on marine natural World Heritage areas (mnWHAs)
Supplementary tables and data underlying the publication: Kuempel, Simmons &amp; Davey (2022) "Assessing the status of existing and tentative marine World Heritage areas reveals opportunities to better achieve World Heritage Convention goals," _Journal of Environmental Management_.

# About this data
This data includes summary statistics as well as the spatial boundaries of current mnWHAs and protected areas that are included in the Tentative World Heritage List (tentative mnWHAs) as of January 2020 across the following metrics used in the analysis: marine wilderness, marine ecoregions, pelagic provinces, at-risk species ranges, and cumulative human impacts. 

**Table S1** presents a summary of marine ecoregions within current mnWHAs. It contains 1 tab of results for each mnWHA (Data), and 1 tab listing each ecoregion within the mnWHAs, the area of the ecoregion, and its rarity across the global ecoregion coverage (Ecoregions).

**Table S2** presents a summary of pelagic provinces within current mnWHAs. It contains 1 tab of results for each mnWHA (Data), and 1 tab listing each pelagic province within the mnWHAs, the area of the pelagic province, and its rarity across the global pelagic province coverage (Provinces).

**Table S3** presents a summary of at-risk species ranges within current mnWHAs. It contains 1 tab of results for each mnWHA (Data), and 1 tab listing each species within the mnWHAs (Species).

**Table S4** presents a summary of cumulative human impacts (2013) within current mnWHAs.

**Table S5** presents a summary of changes in cumulative human impacts (2008-2013) within current mnWHAs.

**Table S6** presents a summary of marine ecoregions within tentative mnWHAs. It contains 1 tab of results for each mnWHA (Data), 1 tab listing each ecoregion within the mnWHAs, the area of the ecoregion, its rarity across the global ecoregion coverage, and if it is represented in the existing mnWHA network (Ecoregions), and 1 tab that lists the corresponding protected area(s) composing each tentative mnWHA, which is linked to the WDPA_PID field from the World Database on Protected Areas that can be used to match sites between datasets (Tentative WHA Legend).

**Table S7** presents a summary of pelagic provinces within tentative mnWHAs. It contains 1 tab of results for each mnWHA (Data), 1 tab listing each pelagic province within the mnWHAs, the area of the pelagic province, and its rarity across the global pelagic province coverage, and if it is represented in the existing mnWHA network (Provinces), and 1 tab that lists the corresponding protected area(s) composing each tentative mnWHA, which is linked to the WDPA_PID field from the World Database on Protected Areas that can be used to match sites between datasets (Tentative WHA Legend).

**Table S8** presents a summary of at-risk species ranges within tentative mnWHAs. It contains 1 tab of results for each mnWHA (Data), 1 tab listing each species within the mnWHAs and if it is represented in the existing mnWHA network (Species), and 1 tab that lists the corresponding protected area(s) composing each tentative mnWHA, which is linked to the WDPA_PID field from the World Database on Protected Areas that can be used to match sites between datasets (Tentative WHA Legend).

**Table S9** presents a summary of cumulative human impacts (2013) within tentative mnWHAs. It contains 1 tab of results for each mnWHA (Data), and 1 tab that lists the corresponding protected area(s) composing each tentative mnWHA, which is linked to the WDPA_PID field from the World Database on Protected Areas that can be used to match sites between datasets (Tentative WHA Legend).

**Table S10** presents a summary of changes in cumulative human impacts (2008-2013) within tentative mnWHAs. It contains 1 tab of results for each mnWHA (Data), and 1 tab that lists the corresponding protected area(s) composing each tentative mnWHA, which is linked to the WDPA_PID field from the World Database on Protected Areas that can be used to match sites between datasets (Tentative WHA Legend).

**Marine_Boundaries (spatial):** we provide the polygon boundaries of the 45 existing and 68 tentative mnWHAs included in the analyses as ESRI shapefiles (Mollweide projection). The polygons have been clipped to exclude terrestrial areas, and fields indicate the total area (area_km) and the marine area (o_area_km) in square kilometers. Each file has a field identifying the respective existing (WDPA_PID) or tentative (TENT_ID) mnWHA ID for linking with data from Tables S1-S10.

# Data sources
**Spatial boundaries** of all mnWHAs were obtained from the World Database on Protected Areas ([WDPA](https://www.protectedplanet.net/)). Only protected areas designated as either marine or mixed terrestrial/marine were included, and only those that are either natural or mixed cultural/natural properties. We excluded mnWHAs whose marine area was too small to be represented by 1x1 km ocean cells (3 existing and 2 tentative mnWHAs). Tentative mnWHA boundaries were estimated based on the description in the Tentative World Heritage List and the corresponding areas in the WDPA.

**Marine wilderness** data was obtained from [Jones et al. (2018)](https://knb.ecoinformatics.org/view/doi:10.5063/F1RR1WFT).

**Ecoregion & Pelagic Province** data ([The Nature Conservancy 2012](https://data.unep-wcmc.org/datasets/38)) was obtained from the global extent of 232 marine ecoregions (coast and shelf areas) ([Spalding et al. 2007](https://doi.org/10.1641/B570707)) and 37 pelagic provinces (surface waters) ([Spalding et al. 2012](https://doi.org/10.1016/j.ocecoaman.2011.12.016)).

**Species ranges** were obtained from the [IUCN Red List of Threatened Species databases](https://www.iucnredlist.org/resources/grid/spatial-data) of terrestrial and marine mammals, birds, amphibians, reptiles, Chondrichthyes, marine fishes, cone snails, lobsters, sea cucumbers, and freshwater shrimps, crabs, and crayfishes. We exclude any species classified as 'data deficient' or 'least concern' as well as any ranges that are known to be extinct. Subspecies were aggregated at the species level.

**Average human impacts** were estimated using the 2013 map of marine cumulative human impacts (CHI) by [Halpern et al. (2015)](https://knb.ecoinformatics.org/view/doi:10.5063/F1S180FS). Average changes in CHI between 2008 and 2013 were also obtained from Halpern et al. (2015). Climate-based pressures include sea surface temperature, UV radiation, ocean acidification, and sea level rise. Ocean-based stressors include fishing (destructive fishing, non-destructive low bycatch, non-destructive high bycatch, pelagic low bycatch, pelagic high bycatch, and artisanal fishing), shipping routes, invasive species, and ocean pollution. Land-based stressors include population density, night-lights, fertilizer pollution, pesticide pollution, and other inorganic pollution. Data for sea level rise, shipping routes, invasive species, and ocean pollution were not available for 2008 and were excluded from CHI change calculations. Ocean acidification, artisanal fishing, and inorganic pollution were also excluded because they did not differ between 2008 and 2013.

# Authors
Caitlin Kuempel

Blake Alexander Simmons (*Data Manager*)

Madeline Davey
