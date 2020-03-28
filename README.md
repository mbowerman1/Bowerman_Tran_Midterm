# Evaluating Racial and Gender Equity in City Government Contracts in Baltimore, New York, and Memphis


## Background

We, as Hopkins students, are also part of the Baltimore community. We are always interested in seeing what and why the city is lacking, as well as any positive developments and potential improvements. Combining that outlook with our interest in equity, we want to explore the business/entrepeneurial landscape of Baltimore city, specifically for groups that are perhaps overlooked or undersupported in their endeavors: women and minorities. In this project, we are studying women- and minority-owned Baltimore businesses contracted by the city government in order to comment on how city government funding and support has been allocated. Above all, we want to discover if these contract percentages are reflective of both business ownership and resident demographics. Additionally, we are comparing our findings to government contracts for women- and minority-owned businesses in New York City and Memphis, to see if the issues and trends we detected are also present. These two cities were chosen because we felt they were, respectively, more liberal and more conservative politically than Baltimore, which we thought might have an impact on the results of government equity programs. They were also chosen due to suitability of available datasets compared to Baltimore's datasets.

## Baltimore Findings
### Certificate distribution by business owner's race and service category in Baltimore
![](Images/contr_dist_byrace_balt.png)

Construction companies made up the bulk of active certificates in 2012, at 38.53%, with Professional Services and Services coming at second and third at 32.43% and 23.65%, respectively.

### Certificate distribution by business owner's race and gender in Baltimore
![](Images/Balt_Contr_Distr_Race_Gender.PNG)

We found that African American men made up the largest MBE subgroup at 44.52% of total certificates, while white women made up the largest WBE subgroup at 23.43%. African American women made up the second largest subgroup for either category, at 14.82%.

### Certificate service category breakdown by gender and race in Baltimore
![](Images/Balt_Contr_Ctgy_Breakdown_Race_Gender.PNG)

Here we see that the traditionally underrepresented groups in professional services are still underrepresented here, with the exception being the Female African American subset.

### M/WBE breakdown, 2012
![](Images/Balt_Cert_Distr.PNG)

38.85% of certificates awarded in Baltimore are classified as WBE, compared to 52.61% of Baltimore businesses which are female-owned, indicating some disparity.

### Baltimore business owner race and gender demographics, 2012
![](Images/Balt_Census_2012_Race.PNG)

![](Images/Balt_Census_2012_Gender.PNG)

Here we see that representation in business ownership is consistent with population demographics. The data suggests that there is no gender imbalance in actual business ownership.

## New York Findings
### M/WBE breakdown, 2020
![](Images/NYC_Contr_Distr_MWBE.PNG)

![](Images/NYC_Cert_Distr_Race_Gender.PNG)

Like Baltimore, New York awards significantly more MBE certificates than any other type, at 45.06% of total active certifications in 2020 (68.28% including overlap with WBE) and 38.80% of total city contracts awarded between 2003-2020 (42.38% including overlap).
Similar to Baltimore, New York's largest MBE subgroup is black males at 18.11%. However, unlike Baltimore, New York's largest WBE subgroup is white women at 31.59% and then black women at 11.78%. Asian men are the second largest MBE subgroup at 15.46%.

### New York City business owner race and gender demographics, 2012
![](Images/NYC_Census_2012_Race.PNG)

![](Images/NYC_Census_2012_Gender.PNG)

Here we see that white business owner's make up 55.07% of New York business owners, while non-MBE certificates make up for about 57.61% of city government contracts, indicating that the demographics of city contracts are fairly reflective of those of business owners. However, women constitute 43.54% of business owners, but only 21.17% of city contracts are WBE-certified, indicating a lack of representation of female business owners in city contracts.

## Memphis Findings
### Memphis business owner race and gender demographics, 2012
![](Images/business_ownership_byrace_mem.png)

![](Images/Memphis_Census_2012_Gender.PNG)

### M/WBE breakdown, 2019
![](Images/cityspending_mem.png)

Here we see Memphis' population demographics (above) and the city's spending on businesses of various fields (below). While the city has a similar population demographic to Baltimore, its MWBE does not receive the same level of support. 

## Data and Information Sources

1) The minority and women's business certifications and city contract awards data for Baltimore from 2012 (uploaded in 2017) was found using the [Open Baltimore data portal](https://data.baltimorecity.gov/ "Open Baltimore").
2) The minority and women's business certifications and city contract awards data for New York City from 2020 was found using the [NYC Open Data portal](https://opendata.cityofnewyork.us/ "NYC Open Data").
3) The general demographic data for all cities from 2012 was found using the [U.S. Census FactFinder portal](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml/ "American FactFinder"). After March 31, 2020, available [here](https://data.census.gov/cedsci/ "Census Data").
4) The general demographic data for Baltimore City (updated 2019) was found using the [U.S. Census FactFinder portal](https://www.census.gov/quickfacts/fact/table/baltimorecitymaryland,US/PST045219/).
5) The FY19 Minority & Women Owned Business (MWBE) Spend Report was found using the [Memphis Data Hub](https://data.memphistn.gov/browse?q=women&sortBy=relevance).

## Data Questions

1) What percentage of the city government's contracts are awarded to Minority and Women's Business Enterprise-Certified companies?
2) Is this percentage reflective of city demographics and business ownership as a whole?
3) What are some interesting trends in city contracts and MBE/WBE-certified companies?
4) Can the data from both Baltimore and other cities be used to create a benchmark for the city government's contract diversity today?

## Data Analysis

We will look at:

1) Businesses' profiles: industry, owner's race and gender, scope and size of work (via contract sizes) for Baltimore
2) If any particular demographic(s) are outperforming others, and why
3) Whether contract details and numbers are reflective of city demographics
4) Comparable data for New York City and Memphis

## Data Manipulation

The following methods and commands were used:

1) Used PivotTables to isolate data and sort entries into respective demographics. Made charts to spot trends and differences.
2) Used IF statements, VLOOKUP, and the Text to Columnn function to organize the datasets.
3) Used Excel's mathematical functions to calculate sums and percentages after refining original data

