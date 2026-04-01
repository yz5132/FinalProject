# Climate-driven changes in sea surface temperature and chlorophyll in the California Current

## Scientific question / hypothesis

In this project, I want to understand how the ocean along the California coast has changed in recent decades under climate warming.

Specifically, I will focus on three questions:

1. Has sea surface temperature (SST) in the California Current increased over time?
2. Over the same period, has surface chlorophyll-a (a proxy for phytoplankton) increased or decreased, and does this change vary across space?
3. On year-to-year time scales, do warmer conditions tend to be associated with lower chlorophyll, and is this relationship influenced by ENSO?

## Datasets

- **Sea surface temperature (SST)**  
  I use monthly SST data from the NOAA Extended Reconstructed Sea Surface Temperature (ERSST v5) dataset. This dataset provides global SST fields on a regular grid and is widely used for studying long-term ocean temperature variability and trends. In this project, I use it to examine large-scale temperature changes in the California Current region.

- **Chlorophyll-a (ocean productivity)**  
  I use monthly satellite-derived chlorophyll-a data from MODIS Aqua Level-3 mapped products (4 km resolution), accessed through the APDRC data server. Chlorophyll-a is used as a proxy for phytoplankton biomass and provides spatially detailed information about surface ocean productivity.

- **ENSO index (Niño 3.4)**  
  I use the Niño 3.4 SST anomaly index from NOAA to represent large-scale climate variability associated with El Niño and La Niña. This dataset is used to explore whether interannual changes in SST and chlorophyll are related to ENSO conditions.

## Study region

The analysis focuses on the California Current coastal region, defined approximately as:

- Latitude: 30°N to 46°N  
- Longitude: 130°W to 116°W  

This region captures the eastern boundary current system along the U.S. West Coast, where coastal upwelling strongly influences ocean temperature and biological productivity.

## Planned analysis

First, I extract the California Current region from each dataset and compute regional mean time series of SST and chlorophyll over the satellite era (approximately 2002–present). Then, I calculate spatial patterns of long-term trends in both SST and chlorophyll to identify where warming and productivity changes are most pronounced. Finally, I analyze interannual variability by comparing SST and chlorophyll anomalies and examining their relationship with the Niño 3.4 index to assess the role of ENSO.