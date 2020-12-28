# ICNC20

This repository contains a *light-weight simulator used to illustrate the use of Delay Tolerant Networks as a supplement for Cloud Connectivity for Rural Remote Patient Monitoring. 


## Code Navigation

* `classification.csv`: A csv file containing the daily acivities and their classifications.
* `activity_tracker.ipynb`: A jupyter notebook containing the analysis of the Mobility Sample Data.
* `simulation.ipynb`: A jupyter notebook for running a simulation and analyzing results of a simulation


## Publications

For more information about the simulator, please refer to our paper. If you use this simulator or code in your own work, we are happy to receive a citation.

Esther Max-Onakpoya, Oluwashina Madamori, Faren Grant, Robin Vander-pool, Ming-Yuan Chih, David K. Ahern, Eliah Aronoff-Spencer, and Corey E.Baker. 2019. Augmenting Cloud Connectivity with Opportunistic Networksfor Rural Remote Patient Monitoring. 

[//]: #[[PDF](https://arxiv.org/pdf/1905.05342.pdf)]


## Comments
Based on the IPUMS ATUS terms and conditions, redistribution of ATUS data is not permitted https://www.atusdata.org/atus/terms.shtml. However, you may obtain an extract from their website: https://www.atusdata.org/atus-action/variables/group

To replicate our work, you would need to obtain the 2017 sample and use the following variables:
| Type | Variable	| Label|  
| --- | --- | --- |
| H	| RECTYPE	| Record Type| 
| H	| CASEID	| ATUS Case ID| 
| H	| METRO	| Metropolitan/central city status| 
| P	| FULLPART	| Full time/part time employment status| 
| A	| ACTLINE	| Activity line number| 
| A	| ACTIVITY	| Activity| 
| A	| START	| Activity start time| 
| A	| STOP	| Activity stop time|


We converted the data from dat to the csv format ('b.csv' file), which had the following headings: RECTYPE, CASEID, METRO, FULLPART, ACTLINE, ACTIVITY, START, STOP. A viable way to do the conversion is by using the syntax file to extract and read the data via SAS, SPSS, or STATA to convert the data to csv. 
