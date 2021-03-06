# beta-im
Correct model specification tests for the beta model

# article
Beta distribution misspecification tests with application to Covid-19 mortality rates in the United States

# authors
José Jairo S. Silva, Francisco Cribari-Neto, Klaus L.P. Vasconcellos

# dataset 1 (states)
file: data_states.csv

columns: 
- state: state
- rate_mort_period1: mortality rate per 100 inhabitants from January 22, 2020 to December 14, 2020 (period 1);
- rate_mort_period2: mortality rate per 100 inhabitants from January 22, 2020 to October 31, 2021 (period 2); 
- rate_mort_period3: mortality rate per 100 inhabitants from December 15, 2020 to October 31, 2021 (period 3);
- rate_vaccination: vaccination rate computed using data until October 31, 2021. 

# datasets 2, 3 and 4 (counties) 
files: data_counties_1.csv (period 1), data_counties_2.csv (period 2), data_counties_3.csv (period 3).  

columns:  
- fips: county code 
- state: state
- county: county 
- rate_mort_period1: mortality rate per 100 inhabitants from January 22, 2020 to December 14, 2020 (period 1);
- rate_mort_period2: mortality rate per 100 inhabitants from January 22, 2020 to October 31, 2021 (period 2);
- rate_mort_period3: mortality rate per 100 inhabitants from December 15, 2020 to October 31, 2021 (period 3);
- rate_vaccination: vaccination rate computed using data until October 31, 2021.

# contact 
cribari at gmail dot com / cribari at de dot ufpe dot br
