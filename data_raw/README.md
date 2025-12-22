# data sources

This folder contains the raw data used for the exercises Phenology Modelling and Digital Soil Mapping, that isn't downloaded again as part of the R script (MODIS and phenocam is downloaded directly when running the phenology script).

*Remark*: Downloading the original datasets is NOT necessary to run the scripts (!). The preprocessed soil data used in the R Markdown script soil_mapping.Rmd is already linked in ../data.

Phenology Modelling: 
- DAYMET climate data: Daily gridded temperature data (Tmax, Tmin) from NASA DAYMET (https://daymet.ornl.gov/), used to calculate mean daily temperature and accumulate growing degree days (GDD). Preprocessed DAYMET data for Boston area 2012 is included in /data_raw for spatial scaling. Original data can be downloaded via the appeears R package. Instructions are included in the R Markdown script. 
- Harvard Phenocam data: Time series of canopy greenness (GCC) and derived phenophase dates. Downloaded via the phenocamr package. Preprocessed data in ../data folder.

Digital Soil Mapping:
- Soil sampling locations and properties: Soil measurements for the canton of Bern, including waterlogging and other soil variables. Original source: Digital Soil Mapping tutorial repository
- Environmental covariates (TIFF files): Topographic, climatic, and hydrological variables used for mapping. The covariates are very large and could not be uploaded to GitHub. If you want to use the original covariates for preprocessing by yourself, please follow this link (https://github.com/geco-bern/tutorial_digital_soil_mapping) to download the full dataset to your computer. 
