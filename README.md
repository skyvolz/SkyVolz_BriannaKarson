# SkyVolz_BriannaKarson
ENV 872 Final Project - CA Wildfires

Wildfires present a pressing environmental challenge in California that has been exacerbated by decades of fire suppression, increasing drought conditions, and a changing climate. This report analyzes wildfire data from the past 75 years, focusing on how climate change has impacted wildfires. Increasingly intense droughts may have a profound affect on Californian fire ecology, contributing to greater fire burn areas, and increased frequency of storms may be a driving higher frequencies of fires caused by lightning striking dry fuels. By providing statistical evidence that wildfire and lightning strike intensity has increased over time, this research can inform policy recommendations, ideally encouraging more proactive fire management strategies to mitigate threats to Californian landscapes.

This project explores the following research questions:
1. How has the size of wildfire burn areas of changed over time?
2. How has the number of wildfires caused by lightning strikes changed over time?

This data for this analysis is sourced from the California Natural Resources Agency GIS database and is serviced by the California Department of Forestry and Fire Protection’s CAL FIRE eGIS. It includes layers that subset from the larger dataset according to year the fire occurred, and size of the burn area in acres. It contains 17,540 records, spanning from the 1950s to May 9, 2025. It is a publicly available feature layer and was last updated on May 9, 2025.

These analyses evaluate how wildfire activity has changed over time, focusing on total burned area and fires caused by lightning. For the burn acreage analysis, fire burn acreage was summed in order to provide monthly and yearly totals. The data was then analyzed at both scales to see if any change over time could be attributed to seasonal patterns.

For the yearly data, a Mann-Kendall test was conducted in order to detect the presence of monotonic trends.
For the monthly data, a time series decomposition was used to analyze the data by trend, seasonal patterns,
and random variation. A Seasonal Mann–Kendall test was run in order to identify seasonal trends in the
monthly data.

The same approach was used for lightning-caused fires, for which monthly and yearly fire counts were
summed and analyzed over time. The yearly data was evaluated using a Mann–Kendall test, since there is
no seasonal pattern at that scale. Monthly data was again broken down using decomposition, and a Seasonal
Mann–Kendall test was used to detect trends while accounting for seasonal changes.

This analysis is fully reproducible in R, with annotated code. To reproduce these analysis in R, download the raw data from this repository, install relevant packages, adjust the file path as needed, and press play to run all code.  
