# SOCAT neural network
Atmospheric carbon dioxide (CO2) dissolved in the ocean moderates the impact of antrhopogenic CO2 emitted into the atmosphere.
The Surface Ocean CO2 Atlas (SOCAT) synthesizes quality controlled surface ocean fCO2 (fugacity of CO2) voering the years 1957-2017. Although this data has reasonable coverage, there are still large regions of the ocean with few to no observations.
Efforts have been made to fill in the gaps using mixed-layer budgets or neural network regression approaches. 

This repository is a testbed for the development of a neural network approach to estimate fCO2 using a suite of driver paramters. 

# Data
- SOCAT dataset is available [here](https://www.socat.info)
- SST, SSS, and MLD are from [GODAS](https://www.esrl.noaa.gov/psd/data/gridded/data.godas.html)
- NPP is available [here](http://orca.science.oregonstate.edu/1080.by.2160.monthly.hdf.vgpm.m.chl.m.sst.php)
- atmospheric CO2 is available [here](https://www.esrl.noaa.gov/gmd/ccgg/mbl/)
