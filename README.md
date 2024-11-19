# Overview

Group Members: Sophia, Ethan, Joseph (Minhyuk), and Lizzie (Elizabeth)

Repo with code and supplementary files for STAT 647 final project

## Scripts

* generate_figures: script to create isotropic cov function visual  
* conus_no2_nngp: script to fit NNGP with n = 10 on conus data  
* rf_gls_test: script to fit RF-GLS


Legacy scripts:
* epa_nngp: script to fit model and generate graphs of EPA data, fits an NNGP with 10 neighors on data for 08/02/2023  
* tempo_test: script to read TEMPO nc4 file, graph data, and optionally fit models

## Data
* C2930725014-LARC_CLOUD_merged_3nods.nc4: NASA satellite data  
	* satellite vertical column density of NO2
	* used in tempo_test, superseded
	* url: https://tempo.si.edu/data_for_scientists.html
* annual_conc_by_monitor_2019.csv
	* All gases from EPA AQS data
	* used in conus_no2_nngp and rf_gls_test for without covariate models
	* url: https://aqs.epa.gov/aqsweb/airdata/download_files.html 
* NO2_CONUS_full_data.csv
	* Subset to NO2 only from EPA AQS data
	* used in conus_no2_nngp and rf_gls_test for with covariate models
	* url: same as annual_conc_by_monitor_2019 plus Sophia's processing
