# beta-im
Correct model specification tests for the beta model

# article
Beta distribution misspecification tests with application to Covid-19 mortality rates in the United States

# dataset 1 (states)
file: data_states.csv

variables: 
- rate_mort_period1: mortality rate per 100 inhabitants from January 22, 2020 to December 14, 2020 (period 1);
- rate_mort_period2: mortality rate per 100 inhabitants from January 22, 2020 to October 31, 2021 (period 2); 
- rate_mort_period3: mortality rate per 100 inhabitants from December 15, 2020 to October 31, 2021 (period 3);
- rate_vaccination: vaccination rate computed using data until October 31, 2021. 

# dataset 2 (counties) 
file: data_counties.csv 

variables: 
- fips: county code 
- state: state
- county: county 
- rate_mort_period1: mortality rate per 100 inhabitants from January 22, 2020 to December 14, 2020 (period 1);
- rate_mort_period2: mortality rate per 100 inhabitants from January 22, 2020 to October 31, 2021 (period 2);
- rate_mort_period3: mortality rate per 100 inhabitants from December 15, 2020 to October 31, 2021 (period 3);
- rate_vaccination: vaccination rate computed using data until October 31, 2021.


