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

### [Vegetation change in the Everglades National Park - 2000 to 2024](portfolio_post/vegetation_portfolio.html)

![National Park Service](https://www.nps.gov/articles/000/images/2A1AF209-1DD8-B71C-07CA99C3B3C02FDAOriginal.jpg?maxwidth=650&autorotate=false&quality=78&format=webp)

(Source: National Park Service, https://www.nps.gov/articles/000/everglades-national-park-south-florida.htm)

The Everglades Natioanl Park is an approximalty 1.5 million area at the southern tip of Florida which consist of 
sawgrass marshes, cypress swamps, hardwood hammokcs, pine rocklands, and extensive mangrove forests ([National Park Service, U.S. Department of the Interior](https://www.npshistory.com/publications/ever/brochures/2015.pdf)).

Climate change may greatly reshape Everglades National Park by flooding areas through rising sea levels, allowing saltwater to invade and harm its freshwater marshes, and increasing the frequency and severity of hurricanes that can erode shorelines and damage ecosystems.

In this brief analysis, we examine the health of Everglades National Park based on the NDVI, covering the period from 2000 to 2024.
The NDVI is a measure used to quantify the density and health of vegetation, and values range from -1 to 1 where low values corresponds to rocks or exposed soil 
and high values indigates greener vegetation, e.g. forests and wetlands ([NDVI](https://www.earthdata.nasa.gov/topics/land-surface/normalized-difference-vegetation-index-ndvi)).

The details to this analysis can be found in [this linked notebook](portfolio_post/vegetation_portfolio.html) (as link in the headline).
The highlights are presented below. 




[back](./)
