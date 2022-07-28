# SpeciesMeanClimate_GBIF


This script was written from an original script by [Georges Kunstler](https://kunstler.github.io/). Its objectives are to:
1. download species presence / absence data from the [GBIF](https://www.gbif.org/) database 
2. download climatic variables for each species occurence from [CHELSA](https://chelsa-climate.org/) database and calculate species mean climate
3. download indices related to the occurence of disturbances (snow water equivalent, mean windspeed, fire weather index) for each point from various databases, and calculate species mean disturbance exposure

To run the script, R package ```targets``` is needed. To launch the script, run ```targets::tar_make()``` from R. 

To run step 3, fire weather index data needs to be downloaded before [here](https://cds.climate.copernicus.eu/cdsapp#!/dataset/10.24381/cds.0e89c522?tab=form) and placed in a folder data/FireWeatherIndex 

For any question, contact Julien BARRERE (julien.barrere@inrae.fr)
