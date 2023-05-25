Replication package for State-level variation in the cumulative prevalence of child welfare system contact, 2015–2019; https://doi.org/10.1016/j.childyouth.2023.106832

All life table estimates available in data/st_tables_combine_tpr_update.csv

variables:
- `state`: US state FIPS code
- `staterr`: US state postal abbreviation
- `varname`: CPS outcome (see paper for definitions)
- `race_ethn`: racial/ethnic group (see paper for definitions)
- `age`: age for risk estimates in subpopulation
- `c_mn`: point estimate for cumulative probability of event by age
- `se_tot`: standard error of point estimate
- `c_upr`: upper bound of 95% confidence interval
- `c_lwr`: lower bound of 95% confidence interval

To replicate paper figures, run `make_state_vis.r`

Replication of life table estimates requires access to NCANDS and AFCARS data, available by request from the National Data Archive on Child Abuse and Neglect. Life table estimates in the paper are derived from NCANDS/AFCARS 2014 - 2020 data, following missing data and multiple imputation procedures described in the paper. Please contact the research team (frank.edwards@rutgers) for replication code for missing data processing if of interest.