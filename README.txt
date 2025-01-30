code_final
______________________________________________________

Contains two Jupyter notebooks:
analysis_yale_NSF.ipnyb
 - reads, cleans, joins the Yale Climate Opinion and NSF data (state-level) from the 
	YCOMD and NSF zipped folders in data_zipped
 - Plots data, runs linear rgeression, checks assumptions.

analysis-county_yomc_vs_fema_pvi.ipnyb
 - reads, cleans, joins the Yale Climate Opinion, SHELDUS and PVI data (county-level)
    from YCOMD, sheldus zipped folders and county_pvi_data.csv in the data_zipped folder
 - Plots data, runs linear rgeression, checks assumptions, runs quantile regression

data_zipped
_______________________________________________________
Contains:

nsf zipped folder: collected NSF funding data from NSF Awards data website (only state-level)

sheldus zipped folder: SHEDLUS 20.0 data from ASU SHELDUS website for all 
                        counties in all states for all hazards and perils from 1960 till 2020
                        (only county-level))

YCOMD zipped folder: Yale Climate Opinion data from 2014, 2016, 2018, 2021
                     (state- and county-level)

county_pvi_data.csv: Partisan strength by county using 2020 US Presidential
                     Results (similar to Cook Political Report PVI data)
                     from the Yale Climate website
