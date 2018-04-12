# Gap-filling with neural networks
Atmospheric carbon dioxide (CO2) dissolved in the ocean moderates the impact of anthropogenic CO2 emitted into the atmosphere.
The Surface Ocean CO2 Atlas (SOCAT) synthesizes quality controlled surface ocean fCO2 (fugacity of CO2) over the years 1957-2017. 
Although this data has reasonable coverage, there are large portions of the where there are no observations.
Efforts have been made to fill in the gaps using mixed-layer budgets or neural network regression approaches.

This repository is a testbed for the development of a neural network approach to estimate fCO2 using a suite of driver paramters. 

# Data Sources 
- SOCAT dataset is available at [https://www.socat.info](https://www.socat.info)
- SST is available at [https://www.esrl.noaa.gov/psd/data/gridded/data.noaa.oisst.v2.html](https://www.esrl.noaa.gov/psd/data/gridded/data.noaa.oisst.v2.html)
- SSS is available at [https://ecco.jpl.nasa.gov/products/latest/](https://ecco.jpl.nasa.gov/products/latest/)
- MLD is available at [https://ecco.jpl.nasa.gov/products/latest/](https://ecco.jpl.nasa.gov/products/latest/)
- Chlorophyll is available at [http://www.globcolour.info](http://www.globcolour.info)
- atmospheric CO2 is available at [https://www.esrl.noaa.gov/gmd/ccgg/mbl/](https://www.esrl.noaa.gov/gmd/ccgg/mbl/)
