GENERAL INFORMATION
Ommitted for double-blind review but will include on final acceptance. 

ACCESS INFORMATION
1. Licenses/restrictions placed onthe data or code
CC0 1.0 Universal (CC0 1.0) Public Domain Dedication

2. Data derived from other sources
N/A

3. Recommended citation for this data/code archive
Will include after review. ???

DATA & CODE FILE OVERVIEW
This data repository consist of 2 data files, 1 code scripts, and this README document, with the following data and code filenames and variables. 
Data files and variables
    1. [Plethodon_Data.csv] [site = the location where individual was collected, species = species of individual; maturity_status = whether the individual was a reproductively mature adult, with NA values indicating that the individual is not mature, including whether the individual was female or male; svl_mm = the snout-vent length of the individual, with NA values indicating a lack of input during initial data collection; sex = whether the individual was male or female; mg = whether the individual had a prominent mental gland; vent = whether the individual had a swollen vent; cirri = whether the individual had visibly enlarged cirri; eggs = whether the individual had visible eggs through the skin; follaces_visible = whether the individual had visible follicles through the skin wall]
    2. [Salamander_Study_Sites.csv] [Study_Area = the general area where the site was located. Generally, this was either within the Coweeta Basin, or at a unique site somewhere else within the Southern Appalachian Mountains; site = the location where the individual was collected; DaymetMDPmm.Apr.Oct.2011.2020 = the Mean Daily Precipitation for that specific site location from April-October between 2011 and 2020, collected from Daymet; DaymetMDTC.Apr.Oct.2011.2020 = the Mean Daily Temperature for that specific site location from April-October between 2011 and 2020, collected from Daymet; DaymetMDVPD.Apr.Oct.2011.2020 = the Mean Daily Vapor Pressure Deficit for that specific site location from April-October between 2011 and 2020, collected from Daymet; Elevation_m = the elevation at that site location, in meters; Aspect = the aspect at that site location; slope = the slope of that site location]

Code scripts and workflow
    1. Plethodon_Hydroclimate_Size_at_Maturity.Rmd - This is the only code file for this manuscript. This does some slightly cleaning and modification of the two files (Plethodon_Data.csv and Salamander_Study_Sites.csv) to determine the smallest mature individual at each site for both males and females. Then, this code runs two generalized linear models, one of which is for the Coweeta Study Region and the other for the broader regional dataset, including the individuals found at Coweeta. 

SOFTWARE VERSIONS
This code was run in R version 4.5.1. 

REFERENCES
N/A