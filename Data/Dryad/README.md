# Data from: Limited conifer regeneration, but widespread regeneration of aspen seedlings following the Cameron Peak Fire, northwestern Colorado

## **Authors and Affiliations**

## Authors

Sarah V. Carter^1^ and Sarah J. Hart^1^

## Affiliations

1 - Department of Forest and Rangeland Stewardship, Colorado State University, 1472 Campus Delivery, Fort Collins, CO 80523, USA

Corresponding author: Sarah J. Hart (email: sarah.hart\@colostate.edu)

## Dataset Description

### Summary

This dataset contains the data required to replicate analyses in Carter and Hart (in review), which examines the patterns and drivers of postfire seedling establishment of aspen at 34 sites within the burn scar of the Cameron Peak Fire, northwestern Colorado. Data was collected in the summer of 2022.

### *Research context*

To understand the potential for severe fire to catalyze shifts to aspen dominated forests, we studied recently burned conifer-dominated forests and asked (1) how does postfire regeneration of conifers and aspen vary across sites? (2) how are aspen and conifer seedlings distributed within sites? and (3) how do site and microsite conditions influence aspen seedling establishment?

## Geographic Coverage

-   **Location**: Cameron Peak Fire scar

-   **Latitude/Longitude Bounding Box**: -105.90370, 40.46133, -105.19902, 40.77812

-   **Elevation range**: 2462-3255 m

-   **Habitat/Ecosystem Type:** upper montane and subalpine forests

## Data Collection Methods

### **Field Methods**

Sites were randomly located using geospatial data describing the extent and severity of the Cameron Peak Fire from the Monitoring Trends in Burn Severity (MTBS) Project (2024b, 2024a) and the extent of pre-fire aspen cover from Cook et al. (2024). We combined these data sources to identify areas that: (a) burned at high or moderate severity and (b) were located \>50 m and \<1000 m away from a pre-fire patch of aspen. Sites were further limited to accessible areas, defined as public land within 1000 m of a road or 500 m away from a trail and no more than 1 km up the trail. To reduce the potential effects of psuedoreplication, all sites were located \>400 meters apart.

At each site, we recorded the coordinates, elevation, slope, aspect, and pre-fire tree-species composition. We then established two perpendicular 2 x 50 m transects that intersected at the midpoint (Andrus et al. 2021). We tallied the presence of all conifer seedlings, aspen seedlings, and aspen root suckers within each transect and recorded their location along the transect within 2 x 2m subplots. Aspen seedlings were differentiated from root suckers using methods outlined by Kreider et al. (2020), which have been demonstrated to be more than 95% accurate (Kreider et al. 2021) and were shown to be effective in our study area (Carter 2024). Along each transect, we also collected information on percent herbaceous cover in three 1 x 1 m quadrats located every 20 m along each transect.

We additionally recorded information on proximity to coarse woody debris, substrate conditions, and microtopographic condition for each aspen seedling. We characterized the microtopography as flat, concave, or convex within 2.5 cm of seedling (hereafter ‘small microtopography’) and within 50 cm of seedling (hereafter ‘large microtopography’). We also recorded the presence or absence of small (diameter = 2.5-10 cm) and large (diameter \>10 cm) coarse woody debris (CWD) within 10 cm of seedling. We also collected microsite conditions at 5 meter intervals along each transect to serve as a baseline of the relative abundance each condition across the site.

### **Data Processing** 

## Data files

The dataset consists of the following files

-   *Site.csv* : This data includes the geographic characteristics of each site sample.

-   *PrefireOverstory.csv* : This data includes information on the presence/absence of each tree species within a 20 m plot centered at the midpoint.

-   *Understory.csv* :This data includes information on the understory percent cover, which was collected in three 1 x 1 m quadrats located every 20 m along each transect.

-   *SeedlingDensity.csv* : This data includes post-fire regeneration densities collected in two perpendicular 2 x 50 m transects that intersected at the midpoint.

-   *SeedlingMicrosite.csv* : This data includes information on the microsite conditions for each aspen seedling we observed.

-   *SiteMicrosite.csv* : This data includes microsite conditions collected at 5 meter intervals along each transect and serves as a baseline of the relative abundance each condition across the site.

-   *README.md* : This file.

## Variable descriptions

### *Site.csv*

-   **Site**: Unique ID for each site

-   **UTM.zone**: the UTM zone of the site

-   **Easting:** Easting of the site (m)

-   **Northing:** Northing of the site (m)

-   **Elevation:** Elevation of the site (m)

-   **Slope**: slope of the plot in degrees

-   **Aspect**: aspect of the plot in degrees from 0 to 360

-   **Topo.Position**: topographic position of the plot (level, sloping, or concave)

### PrefireOverstory.csv

-   **Site**: Unique ID for each site

-   **ABLA**: the presence (1) or absence (0) of subalpine fir (*Abies lasiocarpa*) in the pre-fire site

-   **PICO**:the presence (1) or absence (0) of lodgepole pine (*Pinus contorta*) in the pre-fire site

-   **PIEN**:the presence (1) or absence (0) of Engelmann spruce (*Picea engelmanniii*) in the pre-fire site

-   **PIPO**: the presence (1) or absence (0) of ponderosa pine (*Pinus ponderosa)* in the pre-fire site

-   **PSME**: the presence (1) or absence (0) ofcount of Douglas fir (*Psuedotsuga menziesii*)in the pre-fire site

### *Understory.csv*

-   **Site**: Unique ID for each site

-   **Transect:** ID for the transect (either A or B)

-   **Point**: the distance (m) along transect where the data were collected (0, 20, or 40)

-   **Forb*:*** the percent cover of forbs (0-100)

-   **Shrub**: the percent cover of shrubs (0-100)

-   **Gram**: the percent cover of graminoids (0-100)

-   **Herb**: the percent cover of graminoids (0-100)

### *SeedlingDensity.csv*

-   **Site**: Unique ID for each site

-   **Transect**: ID for the transect (either A or B)

-   **Subplot**: ID for the subplot

-   **ABLA**:count of subalpine fir (*Abies lasiocarpa*) seedlings per subplot

-   **PICO**: count of lodgepole pine (*Pinus contorta*) seedlings per subplot

-   **PIEN**:count of Engelmann spruce (*Picea engelmanniii*) seedlings per subplot

-   **PIPO**: count of ponderosa pine (*Pinus ponderosa)* seedlings per subplot

-   **PSME**: count of Douglas fir (*Psuedotsuga menziesii*)seedlings per subplot

-   **POTR5.sucker**: count of trembling aspen (*Populus tremulodies)* suckers per subplot

-   **POTR5.seedling**:count of trembling aspen (*Populus tremulodies)* seedlings per subplot

-   **Conifer**: count of conifer seedlings per subplot

### SeedlingMicrosite.csv

-   **Site:** Unique ID for each site

-   **Transec**t: ID for the transect (either A or B)

-   **Subplot**: ID for the subplot

-   **Height**: seedling height (cm)

-   **Substrate**: the dominant substrate on which the seedling was found (bryophytes, char, litter, mineral soil, rock, wood)

-   **Small.Topo**: the local topography within 2.5 cm of the seedling (concave, level, sloping)

-   **Large.Topo**: the local topography within 50 cm of the seedling (concave, level, sloping)

-   **Large.CWD**: the presence (1) or absence (0) of coarse woody debris \>10 cm in diameter

-   **Small.CWD**: the presence (1) or absence (0) of coarse woody debris 2.5-10 cm in diameter

-   **Sucker.Dist**: the distance to the nearest aspen sucker

-   **Browse**: the presence (1) or absence (0) of browse damage

### SiteMicrosite.csv

-   **Site**: Unique ID for each site

-   **Transect**: ID for the transect (either A or B)

-   **Point**: the distance (m) along transect where the data were collected (0, 5, 10, 15, 20, 25, 30, 35, 40, 45, or 50)

-   **Height**: seedling height (cm)

-   **Substrate**: the dominant substrate on which the seedling was found (bryophytes, char, litter, mineral soil, rock, wood)

-   **Small.Topo**: the local topography within 2.5 cm of the seedling (concave, level, sloping)

-   **Large.Topo**: the local topography within 50 cm of the seedling (concave, level, sloping)

-   **Large.CWD**: the presence (1) or absence (0) of coarse woody debris \>10 cm in diameter

-   Small.CWD: the presence (1) or absence (0) of coarse woody debris 2.5-10 cm in diameter

-   **Sucker.Dist**: the distance to the nearest aspen sucker

## Data Usage Notes

-   missing values are coded as `NA`

## Related publications

Carter, S. V. and Hart, S. J. (in review). *Limited conifer regeneration, but widespread regeneration of aspen seedlings following the Cameron Peak Fire, northwestern Colorado.*

## Data Citation

Carter, S. V. and S. J. Hart. 2025. Data from: Limited conifer regeneration, but widespread regeneration of aspen seedlings following the Cameron Peak Fire, northwestern Colorado. Dryad. <https://doi.org/XXXX>

## License

This dataset is released under the **Creative Commons Zero (CC0) Public Domain Dedication**, per Dryad policy.

## References

Andrus, R. A., S. J. Hart, N. Tutland, and T. T. Veblen. 2021. [Future dominance by quaking aspen expected following short-interval, compounded disturbance interaction](https://doi.org/10.1002/ecs2.3345). Ecosphere 12:e03345.

Cook, M., T. Chapman, S. Hart, A. Paudel, and J. Balch. 2024. [Mapping Quaking Aspen Using Seasonal Sentinel-1 and Sentinel-2 Composite Imagery across the Southern Rockies, USA](https://doi.org/10.3390/rs16091619). Remote Sensing 16:1619.

Kreider, M. R., K. E. Mock, and L. L. Yocom. 2020. [Methods for Distinguishing Aspen Seedlings from Suckers in the Field](https://doi.org/10.1093/jofore/fvaa030). Journal of Forestry:fvaa030.

Kreider, M. R., and L. L. Yocom. 2021a. [Low-density aspen seedling establishment is widespread following recent wildfires in the western United States](https://doi.org/10.1002/ecy.3436). Ecology 102:e03436.

MTBS Project. 2024b. [MTBS data access: Burned severity mosaics dataset](https://mtbs.gov/direct-download).

MTBS Project. 2024a. [MTBS data access: Burned area boundaries dataset](https://mtbs.gov/direct-download).
