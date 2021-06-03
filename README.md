# ACA_county_treatmenteffects
In this repository, we include the data file with county-level treatment effects for the project "Federal Transfers to Local Areas: The Case of Medicaid Expansion under the Affordable Care Act." By treatment effects, we mean our forecast of federal transfers to each of the U.S. counties as a result of the ACA. 

We include four variables for the forecasted county-level federal transfer. Each was obtained using a different model specification: linear, quadratic, spline, and quantile (details in the paper).

The variables included in the datasets are:

geofips: FIPS county
StateFIPS: FIPS state 
countyname: county name
state_abbrev: state name, abbreviated
state_name state name
TE_eligib_lin: time-invariant forecast of federal transfer to that county triggered by the ACA, obtained from running a linear model
TE_eligib_quadratic: time-invariant forecast of federal transfer to that county triggered by the ACA, obtained from running a quadratic model
TE_eligib_ls: time-invariant forecast of federal transfer to that county triggered by the ACA, obtained from running a linear spline model
TE_eligibles_rate_quan: time-invariant forecast of federal transfer to that county triggered by the ACA, obtained from running a quantile model
