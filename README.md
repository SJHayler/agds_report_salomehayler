# agds_report_salomehayler
Report for Applied Geodata Science II (2025) - Salome Hayler

Submission/last update on the 22.12.2025

This repository contains my solutions for the exercises Phenology Modelling and Digital Soil Mapping. The reports were created with the R version 4.5.1.

Required data can be found in the original sources (/raw_data) and is automatically linked in the R Markdown scripts. For faster computation, some of the data for both reports was downloaded and preprocessed and then stored in the /data folder. The scripts refer to this folder to run without downloading all the data again. The original code for downloading the data is still included in the R Markdown files.

For the Digital Soil Mapping exercise, the covariates constitute an extremely large dataset. Because the TIFF files are very large, this folder could not be uploaded to GitHub. If you want to access the original covariates for preprocessing, please check the data_raw folder in the README, which contains a link to the repository for the soil data. This allows downloading the full dataset to your personal computer. However, downloading the original covariates is *not necessary* to run the R Markdown scripts, as they are already linked to the preprocessed covariates in the /data folder.

Remark: The knitting process may take some time, especially for the Phenology Modelling report, because MODIS and Phenocam data need to be loaded and processed. Additionally, steps such as hyperparameter tuning for random forests (2000 trees) can increase computation time. The loop for automatic installation of missing packages at the start may also slow down the knitting process.

All references and data sources used are indicated in the respective R Markdown or knitted HTML files.
