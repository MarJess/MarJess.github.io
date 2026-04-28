---
layout: default
---

## Earth Data Analytics Projects

### First interactive map

The Frankfurt Airport is the busiest airport by passenger transport in Germany and one of the busiest in Europe (6th place). 
In addition, it is the busiest airport in Europe by cargo traffic. 
Even though it is one of the largest airports in Europe, it is located close to the city of Frankfurt am Main and can be reached in no time by car or public transport.

<embed type="text/html" src="img/ffm_airport.html" width="600" height="600">

### [Climate Change - Kleiner Feldberg, Germany](portfolio_post/climate_change_portfolio_kleiner_feldberg_20250930.html)

The Kleiner Feldberg is the second-highest mountain in the Taunus mountain range with an elevation of 826 m (2,710 ft), right next to largest montain called Großer Feldberg.
On the top of the Kleiner Feldberg, there is the Taunus Observatory, which was build in 1913 and is still in use for meteorologocal and geophysical measurements. This station was selected because it is close to my home town of Frankfurt.

The annual averages daily maximum and minimum temperatures are displayed in the following plot.
The year 1945 has significantly fewer observation days, covering only about 16% of the year. In 1946, about 75% of the year is covered. 
Since 1945 in particular cannot represent the annual average, we will not consider this year for the trend analysis and they are not displayed.

<embed type="text/html" src="img/annual_kl_feldberg_temperatures-4.html" width="500" height="350">

A **linear regression using the least squares method (OLS)** was performed on the annual average values of the daily maximum and minimum temperatures in order to obtain the temperature trend (see following plot).
The plot alone gives the impression that the trends for annual averaged maximum and minimum temperatures are slightly different. 
Looking at the slopes, the maximum temperature rises by around **0.0221 degrees per year** over the period, and the minimum temperature by around **0.0184 degrees per year**.

![Alt text for the image](img/kleiner_feldberg_trend.png "Optional title text on hover")

The results of this analysis, with a stronger increase in the trend of maximum temperatures than in the trend of minimum temperatures, indicate an increase in diurnal temperature range (DTR). 
This is in line with the most recent research in DTR, showing an increase in DTR, mainly due to accelerated warming of the maximum daily temperature. This is thought to be related to a decrease in global cloud cover and the associated increase in solar radiation.

Further details on the analysis and conclusion can be found in this [linked notebook](portfolio_post/climate_change_portfolio_kleiner_feldberg_20250930.html) (as link in the headline). 

### [Annual Migration Patterns of the Canada Goose](portfolio_post/migration_portfolio_canada_goose.html)

![Canada Goose Picture](https://www.hawkeye.ca/images/blog-canada-goose1.webp)

The Canada goose (Branta canadensis) has a black head and neck, white cheeks, white under its chin, and a brown body. 
Even though the name suggests its origin, it is more widespread than one might think. 
It is native to the arctic and temperature regions of North America, but can be found 
in Europe, New Zealand, Japan, Chile, Argentina,and the Falkland Islands (Long, 1981).

In the chracteristic V-formation, they fly to their wintering grounds and their breeding grounds in winter,
often a symbol used for the changing seasons in North America. 
The migration routes of the Canada goose are not genetically determined, but are passed down within the various subpopulations. 
Young geese learn the migration route and the location of their winter quarters during migration with their parents. 
Some of the most southerly subpopulations are resindet birds or partial migrants, while more northerly ones are distinct migratory. 
Thus, some of the more northerly populations sometimes pass their sourthern populations that remain closer to their breeding grounds and spend the winter month much further south.

This brief analysis of the migration of the Canada goose is based on the <a href="https://www.gbif.org" target="_blank">GBIF</a> database from 2024.
This year's occurrences were linked to maps of the ecoregions and then grouped by ecoregion and month. 
Very rare occurrences (three or fewer) were excluded from the analysis. 
In addition, the grouped occurrences were normalized to the size of the ecoregions.
The occurrences were also normalized spatially and temporally.
The details to this analysis can be found in [this linked notebook](portfolio_post/migration_portfolio_canada_goose.html) (as link in the headline). 

The following plot shows the normalized occurrences per ecoregion and month of the year. 

<embed type="text/html" src="img/canada_goose_2.html" width="600" height="400">

It can be seen that, based on the GBIF database, the occurrences are mainly limited to North America, Europe, and New Zealand. This agrees with the literature, which identifies these as the main areas of occurrence (e.g. <a href="https://www.thoughtco.com/canada-goose-bird-facts-4584329" target="_blank">Canada Goose Facts</a>).
The Canada goose was introduced to England as early as the 17th century. In the 19th century, the Canada goose was also recorded as ornamental poultry on the European mainland. In New Zealand, however, the Canada goose was introduced not as ornamental poultry but as game for hunting. 

I would like to highlight a few special features that stood out in the graphic representation of the migration: 
- In North America and Europe, there is a noticeable migration toward higher northern latitudes during the summer months. However, a certain number always remain in southern latitudes. This reflects the mixture of different subspecies and their migration patterns. Some of the most southerly subpopulations are resindet birds or partial migrants, while more northerly ones are distinct migratory which migrates to warmer regions in the south during winter. 
- The occurrences in New Zealand are relatively consistent throughout the year, indicating that there is little migration there. Migration here occurs more from the South Island to the North Island and vice versa. 
- Particularly in June, a considerably higher occurrence can be observed in the southern part of Hudson Bay and James Bay. A very recent publication by <a href="https://nsojournals.onlinelibrary.wiley.com/doi/full/10.1002/wlb3.01062" target="_blank">Sorais et al. (2023)</a> described movement patterns and habitat use of molt migrant Canada geese along the east coast of James Bay. They report that the number of Canada geese breeding in temperate zones along the Atlantic and Mississippi flyways has increased significantly since the 1980s. Geese spent 2.8 ± 0.6 days (mean ± standard error of the mean) at 3.2 ± 0.6 resting places (mainly mudflats and salt marshes) from the first week of June in spring and 3.8 ± 1.8 days at 2.0 ± 0.5 resting places (mainly inland waters, moors, and mudflats) from the first week of September on their return south. The increased occurrence in June in particular coincides with the GBIF occurrences.

A detailed analysis of the migration behavior of Canada geese would be very interesting. To this end, it would be useful to have longer records covering several years in order to identify changes in migration patterns caused by factors such as climate change and hunting behavior, e.g. populatioin change due to more hunting of Canada geese.

### [Vegetation change in the Everglades National Park - 2000 to 2024](portfolio_post/vegetation_portfolio_20251126.html)

![National Park Service](https://www.nps.gov/articles/000/images/2A1AF209-1DD8-B71C-07CA99C3B3C02FDAOriginal.jpg?maxwidth=650&autorotate=false&quality=78&format=webp)

(Source: National Park Service, https://www.nps.gov/articles/000/everglades-national-park-south-florida.htm)

The Everglades Natioanl Park is an approximalty 1.5 million acres area at the southern tip of Florida which consist of 
sawgrass marshes, cypress swamps, hardwood hammokcs, pine rocklands, and extensive mangrove forests ([National Park Service, U.S. Department of the Interior](https://www.npshistory.com/publications/ever/brochures/2015.pdf)).

<embed type="text/html" src="img/everglades_satellite.html" width="600" height="400">

Climate change may greatly reshape Everglades National Park by flooding areas through rising sea levels, allowing saltwater to invade and harm its freshwater marshes, and increasing the frequency and severity of hurricanes that can erode shorelines and damage ecosystems.

In this brief analysis, we examine the health of Everglades National Park based on the NDVI, covering the period from 2000 to 2024.
The focus was placed on the month of September, following the hottest days of summer and the peak season for tropical storms and hurricanes
The NDVI is a measure used to quantify the density and health of vegetation, and values range from -1 to 1 where low values corresponds to rocks or exposed soil 
and high values indigates greener vegetation, e.g. forests and wetlands ([NDVI](https://www.earthdata.nasa.gov/topics/land-surface/normalized-difference-vegetation-index-ndvi)).

The details to this analysis can be found in [this linked notebook](portfolio_post/vegetation_portfolio_20251126.html) (as link in the headline).
The highlights are presented below. 

A split of the time series and comparison of the periods 2000 to 2012 and  2013 to 2024 shows that coastal areas and areas adjacent to urban and 
metropolitan areas of the national park in particular show a decrease  in NDVI, while central areas of the park show an increase in NDVI.
Because the Everglades sit at a very low elevation, even slight sea-level rise can have major impacts. Saltwater can move farther into freshwater marshes and kill freshwater plants, while higher sea levels can raise groundwater levels and increase vegetation in the park’s interior

<embed type="text/html" src="img/everglades_diff.html" width="600" height="400">

The time series of NDVI values was compared inside and outside the National Park, showing larger values of NDVI
inside the Park than outside. This is also due to the fact that there is an 
urban area adjacent to the national park.
The following shows the difference between inside and outside the park. 

<embed type="text/html" src="img/everglades_in_out_diff.html" width="500" height="400">

Severals years show substantial decrease of the difference. 
In 2017 in particular, there was a more drastic decline in the difference compared to previous and subsequent years. 
This is the year, where hurricane Irma striked the Everglades with landfall as a Category 4 storm.
On September 10, the hurricane moved northward through Florida and Georgia and did extensive damage to the forest canopy
([USGS](https://www.usgs.gov/special-topics/lcmap/science/lcmap-change-stories-hurricanes-everglades) and the following satellite image).

![hurricane irma](https://www.weather.gov/images/mfl/Hurricane%20Irma/SatAnimation.gif)

(Source: NOAA weater service,  https://www.weather.gov/mfl/hurricaneirma)


### [Comparison of daily temperature variability trends from various stations distributed globally](portfolio_post/climate_final_project.html)

Global climate change is altering temperature conditions and influencing water and carbon exchange in ecosystems. An important indicator is the daily temperature range (DTR), i.e., the difference between day and night temperatures. Earlier studies (Kar et al., 1993) mostly reported declining DTR trends, while more recent studies (Zhong et al., 2023; Liu et al., 2024) suggest a shift toward mostly increasing trends since the late 1980s to early 1990s. Using measurement stations distributed worldwide, the planned study will evaluate how DTR trends differ at different locations, determine whether there is an overall positive or negative trend, and compare these results with those from the current literature.

Climate Data were taken from
Meteorological data was taken from [Global Historical Climatology Network daily (GHCNd)](https://www.ncei.noaa.gov/products/land-based-station/global-historical-climatology-network-daily#:~:text=The%20Global%20Historical%20Climatology%20Network,suite%20of%20quality%20assurance%20reviews.).
Ten stations were selected, distributed globally and marked in the map below.

<embed type="text/html" src="img/station_overview.html" width="600" height="400">

The details to this analysis can be found in [this linked notebook](portfolio_post/climate_final_project.html) (as link in the headline). This includes the analysis of seasonal and annual trends. In the following, we will only discuss the annual trends. 

Annual trends were calculated only for years with fewer than 60 missing days, except for Ushuaia and Praia, due to limited data. Following Zhong et al. (2023), each station’s time series was split into pre-1990 and post-1990 periods, revealing that many stations exhibit notable or even reversed trend changes between the two intervals.

Annual trends from the stations:

| Station   | Before 1990 [°C/decade] | After 1990 [°C/decade]  |
| :-------  | :------: | -------: |
| Svalbard  | 0.08   | -0.3  |
| Barrow    | -0.16  | -0.19|
| Salt Lake City  | -0.4 | -0.36 |
| Kleiner Feldberg| -0.05| 0.04 |
| Kathmandu | 1.11 | 0.41 |
| Praia     | -  | -0.7 |
| Mendoza   | -0.87  | -0.53 |
| Ushuaia   | 0.45 | -0.57 |
| Cape Grim 2 | -0.02 | 0.2 |
| Cape Grim 2 | -  | 0.11 |

![Alt text for the image](img/annual_trends_stations.png "Optional title text on hover")

Most stations show a negative DTR trend after 1990, seemingly contradicting recent studies that report a shift to positive trends. However, when comparing these station-level results with the spatial trend patterns in the GSOD dataset (1991–2020) presented by Zhong et al. (2023), the findings are generally consistent.

![Zong_et_al_2024_2](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41467-023-43007-6/MediaObjects/41467_2023_43007_Fig2_HTML.png?as=webp)

(Source: Zhong et al. (2023): Reversed asymmetric warming of sub-diurnal temperature over land during recent decades)


### [Vegetation data to estimate depression prevalence in Seattle](portfolio_post/portfolio_urban_greenspace.html)

Increasing urbanization has raised concerns about mental health, highlighting the importance of urban green spaces. Although evidence suggests that green spaces may reduce the risk of depression and anxiety, uncertainties remain about the strength and consistency of this relationship. A recent meta-analysis by [Liu et al., 2023](https://www.sciencedirect.com/science/article/abs/pii/S0013935123011076) found that greater green space coverage and higher NDVI levels are associated with lower risks of depression and anxiety. Seattle, a U.S. city with relatively high depression prevalence, also faces climate-related stressors such as flooding, pollution, and wildfire smoke that may further affect residents’ mental health. This analysis examines the relationship between depression prevalence and urban green space in Seattle by calculating landscape metrics—patch, edge, and fragmentation—using depression data from the [CDC PLACES](https://www.cdc.gov/places/index.html) dataset and urban green space imagery from the Microsoft Planetary Computer STAC catalog.
The details to this analysis can be found in [this linked notebook](portfolio_post/portfolio_urban_greenspace.html) (as link in the headline)

The U.S Center for Disease Control (CDC) provides severeal health variables through their [Places Dataset](https://www.cdc.gov/places/index.html).
Here we look at the adult depression for Seattle. 
Thd following plot shows the depression prevalence in Seattle census tracts. 

<embed type="text/html" src="img/depression_census.html" width="600" height="400">

The map reveals data gaps in some census tracts. Higher depression prevalence appears west of the airport and industrial areas and in north-central Seattle, but without clear clustering.
I first suggestion is that pollution from industrial activity and the airport may play a role, though lower depression rates east of these areas suggest other factors are involved. 
Higher depression rates also tend to coincide with higher crime levels.
To determine the relationship between depression and urban green spaces, we use data from the Microsoft Planetary Computer SpatioTemporal Access Catalog (STAC) and calculate the metrics percentage vegetation, mean patch size, and edge density. The follwing plots show again the depression prevalence but also the vehetation edge density of Seattle 

<embed type="text/html" src="img/ndvi_census.html" width="600" height="400">

Comparing these two figures, a direct correlation cannot be immediately discerned. 
In general, census tracts with higher prevalence also have slightly higher values in vegetation edge density. 

In the final step, we test the possibility of determining depression prevalence from vegetation metrics. 
For this, we use the linear ordinary least squares (OLS) regression. 
The most suitable data from our vegetation dataset are edge density and mean patch size, with mean patch size being logarithmically transformed to eliminate excessive skewness
(see individual steps in the [this notebook](portfolio_post/portfolio_urban_greenspace.html)).

Predicted and actual depression data were finally compared to determine the quality of the model. The following figure shows the model error. 

<embed type="text/html" src="img/error_chloropleth.html" width="600" height="400">

The error analysis indicates that the model systematically underestimates areas with high depression prevalence and overestimates others, implying that vegetation and related metrics alone are inadequate for explaining adult depression patterns. Socioeconomic factors such as crime, income, and financial stability are likely more influential. Seasonal conditions—particularly limited sunlight and Seattle’s persistently cloudy climate—may also contribute through elevated rates of seasonal affective disorder.

##### Sources 
Centers for Disease Control and Prevention. PLACES: Local Data for Better Health. Accessed [2026-01-30]. https://www.cdc.gov/places

Ziquan Liu, Xuemei Chen, Huanhuan Cui, Yuxuan Ma, Ning Gao, Xinyu Li, Xiangyan Meng, Huishu Lin, Halidan Abudou, Liqiong Guo, Qisijing Liu (2023): Green space exposure on depression and anxiety outcomes: A meta-analysis. https://doi.org/10.1016/j.envres.2023.116303

Cascade PBS. Accessed [2026-01-30]: Climate change takes a toll on Seattleites' mental health. https://www.cascadepbs.org/environment/2022/06/climate-change-takes-toll-seattleites-mental-health/

Microsoft Planetary Computer SpatioTemporal Assess cataloc (STAC). Accessed [2026-01-30]. https://planetarycomputer.microsoft.com/catalog


### [Land cover classification at Kawartha Lakes (Ontario)](portfolio_post/kawartha_clustering_portfolio.html)

The Kawartha Lakes are several lakes in south-central Ontario, Canada. Together, they form the upper watershed of the Trent River. 
These lakes ranges in size from 2 to 83 $km^2$.

The Trent-Severn Waterway makes its way through many of these lakes. 
This area is also very well known for its recreational tourism. 

We use a k-means **unsupervised** clustering algorithm to group pixels by similar spectral signatures. 

We will use the [harmonized Sentinel/Landsat multispectral
dataset](https://lpdaac.usgs.gov/documents/1698/HLS_User_Guide_V2.pdf).
The data can be accessed with an [Earthdata
account](https://www.earthdata.nasa.gov/learn/get-started) and the
[`earthaccess` library from
NSIDC](https://github.com/nsidc/earthaccess). 

Every step of this analysis can be seen in [this notebook](portfolio_post/kawartha_clustering_portfolio.html)).

<embed type="text/html" src="img/kawartha_site_plot.html" width="600" height="400">

This site is located in south-central Ontario, Canada. 
The cain of lakes is clearly visible. North of the lakes is a predominantly natural area with forests, whereas around the lakes and south of them, agricultural land with fields predominates. In additon, lager cities can be found south of the lakes, for example Peterborogh and Kawartha Lakes.

Using the Elbow method, we first determined the optimal number of clusters. 
It appears that a number of 4 to 5 clusters is optimal, so we decided on 5. 
![Alt text for the image](img/kawartha_elbow_plot.png "Optional title text on hover")

The following figures show the RGB composite image with and the clustered image.

<embed type="text/html" src="img/rgb_kmeans_combi_plot.html" width="600" height="400">

The k-means classification shows good results for the area under investigation. The excellent classification of the water areas (in this case in orange) is particularly evident. The division of the clusters south and north of the lakes is also clearly visible. Red and purple clusters dominate south of the lakes, while green and blue clusters dominate north of the lakes. This reflects the division of land use or land type, with urban and agricultural areas south of the lakes and natural, forested areas north of the lakes.

##### Sources 

https://parks.canada.ca/lhn-nhs/on/trentsevern/info/infonet/niveau-eau-water-levels

https://thecanadianencyclopedia.ca/en/article/kawartha-lakes


### [Historical and future habitat suitability of Indiangrass](portfolio_post/habitat_suitability_indiangrass.html)

Sorghastrum nutans (Indiangrass) is a widespread, resilient grass found across most of the United States, from Quebec and Maine to Arizona and northern Mexico, and east to Florida.
It grows in prairies, savannas, open woodlands, and roadsides, thriving in well-drained soils with a wide range of textures and pH (about 5–7.8). It typically reaches 3–8 feet tall and can grow from sea level up to about 7,000 feet, often on south- to southwest-facing slopes.
Indiangrass tolerates varied environmental conditions, including 12–40 inches of annual rainfall and has deep roots (at least 24 inches), contributing to its adaptability.

Two sites were selected for this project, both of which are relatively far apart.
One is the Richard Bong Recreation Area (RB) in Wisconsin, and the other is the Balcones Canyonlands National Wildlife Refuge (BC) in Texas. This gives us two sites that may respond differently to a changing climate and, consequently, to the habitat suitability of Indian grass.

We use the fuzzy logic model to assess habitat suitability for two climate periods: a historical period (1970–1999) and a future period (2071–2099). For the future period, we consider the RCP8.5 emissions scenario, which assumes high emissions of greenhouse gases. A detailes analysis can be found [this notebook](portfolio_post/habitat_suitability_indiangrass.html)).

The following figures show the data used for the fuzzy logic model.

![Alt text for the image](img/harmonized_RB.png "Optional title text on hover")

![Alt text for the image](img/harmonized_BC.png "Optional title text on hover")

In addition to precipitation and temperature data from historical records and future scenarios, soil pH, elevation, aspect, and slope information are used.

The following plots show the habitat suitability for the two sites and for historical and future climate. 
It is based on the variables given above, which are included in the fuzzy logic model. 
0 means a poor habitat suitability and 1 means good suitability. 

![Alt text for the image](img/suitability_richard_bong_historical.png "Optional title text on hover")

![Alt text for the image](img/suitability_richard_bong_future.png "Optional title text on hover")

![Alt text for the image](img/suitability_balcones_canyonlands_historical.png "Optional title text on hover")

![Alt text for the image](img/suitability_balcones_canyonlands_future.png "Optional title text on hover")


By comparing a northern site (Wisconsin) and a southern site (Texas) between historical (1970-1999) and futute (2071-2099) periods, the analysis highlights a substantial geographical divergence. 

* Northen site: habitat suitability is expected to remain stable ot increrase slighty. Temperature will rise within the plant's tolerance and slight increase in precipitation.
* Southern site: habitat suitability is projected to decline. Drastic decreasing precipitation and rising temperature.

This study concludes that under extreme climate change, the ideal habitat for Indiangrass will shift northward. 
Southern regions may become too arid and hot to sustain historical population levels, while northern regions may become more favorable. 

### Final Project: Equivalent Latitude - Comparison of two PV-based calculations and comparison of two reanalysis products

The equivalent latitude is a commonly used quasi-Lagrangian coordinate that is primarily used in the stratosphere. 
It is defined as the latitude that encloses a circle centered at the pole with the same area as the isoline of an atmospheric field (e.g. potential vorticity (PV)).

Since this is a quasi-Lagrangian coordinate, it moves along with the air masses, thereby eliminating adiabatic transport.
This separates dynamic variability from chemical changes, such as photochemical ozone depletion in the Arctic or Antarctic vortices.
This coordinate is therefore frequently used for climatological studies of the stratosphere, 
particularly when comparing model data with observational data, where the observational data are often limited in time and space.

Traditionally, potential vorticity fields are used on isentropic surfaces to determine equivalent latitude, based on reanalysis data.
It is assumed that the PV value is constant within each grid cell of the reanalysis field, and all grid cells whose PV value is below a given threshold are identified.
The areas of all selected cells are added together, and the equivalent latitude is calcualted from the totoal are. This method is called Piecewise-Constant method. 

In their 2013 publication, Anel et al. presented an extension of this method. In this approach, PV is not treated as a constant between grid cells but can vary within the cell. 
A contour mapping function interpolates PV isolines. The geometric areas are calculated and converted to equivalent latitude. 
This method is called the Region of Interest method, and the authors state that it is significantly faster and more accurate than the traditional method. They use the IDL programming language for this purpose. 

In this project, we first intend to test both methods using current reanalysis products, which have significantly higher resolutions than those used in the original publication. We will use two reanalysis products: MERRA-2 and ERA5 (se following table for key information). Additionally, we aim to compare these two reanalysis products. The calculations will be implemented in Python, which has not yet been done for either method. Only one freely available Python package (pyvortey) was found that includes the piecewise method.
In addition to reanalysis products, MLS satellite data (ozone and temperature) and the [SWOOSH]([https://www.earthdata.nasa.gov/topics/land-surface/normalized-difference-vegetation-index-ndvi](https://csl.noaa.gov/groups/csl8/swoosh/)) product from NOAA are also used.

| MERRA-2 (NASA) | ERA5 (ECMWF) | 
| :--- | :--- | 
| 1980 - today | 1940 - today | 
| 0.5°x0.635° (lat x lon) |  0.25°x0.25° (lat x lon)  | 
| 3 - hourly |  1 - hourly  | 

The following are some key findings of this analysis.
The two follwoing plots show PV against Equivalent Latitude for severeal isentropic levels (350 K to 750 K) for both methods and both reanalysis products. 
The key findings are that the greatest differences between the two methods are primarily observed in the respective summer hemispheres, 
where PV gradients on isentropic surfaces are significantly weaker, as well as at the poles, where small-scale features are present. 
Overall, differences are in der range of around 0.1° to 0.6° and typically slightlz larger for MERRA-2 (slightly courser resolution compared to ERA5).
Thus, the differences between the two methods are very small and negligible for most applications of the coordinate.

![Alt text for the image](img/pw_roi_comparion_ERA5_20200630_1200.png "Optional title text on hover")
![Alt text for the image](img/pw_roi_comparion_MERRA2_20200630_1200.png "Optional title text on hover")

We also examined the differences between the two reanalysis products when using the same method. 
To do this, we calculated Equipment Latitude fields for days in 2020 (though only at 12:00 UTC). 
Among other things, the root mean square deviation (RMSD) of MERRA2 and ERA5 was calculated for each season and for various latitude ranges (see following plot).
Here, larger differences between MERRA-2 and ERA5 are visible in the summer hemisphere mid and high-latitudes and lower isentropic leveles. 
The differences become less pronounced as isentropic height increases, but in the spring, differences can still be observed in the mid-latitudes of the Southern Hemisphere.
This is the time when the Antarctic vortex breaks up and forms filaments, which may be captured differently in these two reanalyses. 

![Alt text for the image](img/era5_merra2_comp_season_PW.png "Optional title text on hover")

To determine which Renalyse product tends to be more accurate, we looked at ozone from MLS satellite data for selected days and calculated the equivalent latitude for these days using ERA5 and MERRA2. 
We then determined the zonale mean of ozone, using both the standard geographical latitude and the equivalent latitudes from MERRA2 and ERA5. 
Since ozone levels should follow global dynamic pattens, one would expect a more compact distribution across Equivalent Latitude, and thus smaller standard deviations in the mean values. The following plot shows the comparison for June 30, 2020. 
It is evident that both reanalyses, when applied to equivalent latitudes in the Southern Hemisphere—and thus during winter—result in a better representation of the zonal mean with a lower relative standard deviation. Air masses within and outside the polar vortex are better resolved. However, both reanalyses show a higher relative standard deviation in the Northern Hemisphere. 

![Alt text for the image](img/Multi_MLS_20200630.png "Optional title text on hover")

The results obtained using the SWOOSH data will be discussed in greater detail as this project continues in the summer semester. 

#### Summary
The Piecewise-Constant and Region of Interest method show only small differences (0.1° to around 0.6°). 
However, the traditional Piecewise-Constant method is currently significantly faster to compute in Python, so it continues to be the preferred method here. 
The greatest differences are found in regions with weak PV gradient and/or near the poles, where the areas become smaller.
MERRA-2 and ERA5 are overall comparable, but show larger differences in respective summer hemispheres (weak PV gradients) and lower isentropic levels (more structure).
PV-based Equivalent Latitude seems to perform better in winter hemisphere, where PV gradient on isentropes are stronger.
SWOOSH monthly zonal mean ozone distribution - not really satisfying (not shown herer). 
Next step is look at N2O from SWOOSH (waiting for data) and move to Machine Learning approach.

Sources: 

Añel JA, Allen DR, Sáenz G, Gimeno L, de la Torre L (2013) Equivalent Latitude Computation Using Regions of Interest (ROI). PLoS ONE 8(9): e72970. https://doi.org/10.1371/journal.pone.0072970

Copernicus Climate Change Service, Climate Data Store, (2023): ERA5 hourly data on pressure levels from 1940 to present. Copernicus Climate Change Service (C3S) Climate Data Store (CDS). DOI: 10.24381/cds.bd0915c6 (Accessed on 20-04-2026)

Global Modeling and Assimilation Office (GMAO). (2015). MERRA-2 inst3_3d_asm_Np: 3d, 3-Hourly, Instantaneous, Pressure-Level, Assimilation, Assimilated Meteorological Fields V5.12.4. Goddard Earth Sciences Data and Information Services Center (GES DISC). https://doi.org/10.5067/QBZ6MG944HW0

Schwartz, M. (2021). MLS/Aura Level 2 Ozone (O3) Mixing Ratio V005. NASA Goddard Earth Sciences Data and Information Services Center. https://doi.org/10.5067/AURA/MLS/DATA2516 Date Accessed: 2026-04-20

Schwartz, M. (2021). MLS/Aura Level 2 Temperature V005. NASA Goddard Earth Sciences Data and Information Services Center. https://doi.org/10.5067/AURA/MLS/DATA2520 Date Accessed: 2026-04-20

[back](./)


