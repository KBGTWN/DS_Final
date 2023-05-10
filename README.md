# DS_Final

Authors: Thomas Adams & Keegan Brown
Submission Date: 05/10/23

Github Page link: https://kbgtwn.github.io/DS_Final/


Files used for data analysis are too large to store on the repo. To recreate the files from IPUMS, visit the following website and select the following variables. Note, these must be pulled twice. One in a standard format, and one in the hierarchical format. Hierarchical is required for the vacancy rate by puma analysis in the EDA section of the .qmd. 

##IPUMS: https://usa.ipums.org/usa-action/variables/group

Data source citation: 

Steven Ruggles, Sarah Flood, Matthew Sobek, Danika Brockman, Grace Cooper,  Stephanie Richards, and Megan Schouweiler. IPUMS USA: Version 13.0 [dataset]. Minneapolis, MN: IPUMS, 2023. https://doi.org/10.18128/D010.V13.0

##Variables:

From 2021 ACS - 1-year

- Census year (Year)
- IPUMS sample identifier (SAMPLE)
- Original Census Bureau household serial number (CBSERIAL)
- Household serial number (SERIAL)
- Household weight (HHWT)
- Household Type (HHTYPE)
- Household cluster for variance estimation (CLUSTER)
- Census region and division (REGION)
- State (FIPS code) (STATEFIP) 
- County (FIPS code) (COUNTYFIP)
- Population-weighted density of PUMA (DENSITY)
- Metropolitan status (METRO)
- Public Use Microdata Area (PUMA)
- Household strata for variance estimation (STRATA)
- Group quarters status (GQ)
- Ownership of dwelling (tenure) [general version] (OWNERSHP)
- Ownership of dwelling (tenure) [detailed version] (OWNERSHP)
- Annual property taxes, 1990 (PROPTX99) 
- Monthly contract rent (RENT)
- Monthly gross rent (RENTGRS)
- Total household income (HHINCOME)
- Food stamp recipiency (FOODSTMP)
- House value (VALUEH)
- Vacancy status (VACANCY)
- Kitchen or cooking facilities (KITCHEN)
- Age of structure, decade (BUILTYR2)
- Number of bedrooms (BEDROOMS)
- Data quality flags


Fair market housing data pulled from the following link for county level: 
https://www.huduser.gov/portal/datasets/fmr.html#2021_data 






