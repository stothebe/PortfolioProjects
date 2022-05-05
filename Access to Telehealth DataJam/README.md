# DataJam
Submission for 2022 Health Equity DataJam. 



## Datasets
2021 County Health Rankings National Data collected by The County Health Rankings & Roadmaps, a program of the University of Wisconsin Population Health Institute.
https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation

2018 Social Determinants of Health Database collected by Agency for Healthcare Research and Quality. https://www.ahrq.gov/sdoh/data-analytics/sdoh-data.html

2021 HPSA - Mental Health Data collected by Health Resources & Services Administration (HRSA). https://data.hrsa.gov/data/download

2020 Broadband Data collected by Microsoft. https://github.com/microsoft/USBroadbandUsagePercentages/tree/master/dataset

2010 US Census County Land Area. http://data.ctdata.org/dataset/land-area-by-county


## Tools
SQL Server for data cleaning and analysis 

Tableau for visualization. Link to visualization: https://public.tableau.com/app/profile/sarah.bang/viz/ClosingtheDigitalDivideTelehealth/Story1

## Methods

Demographic information including race/ethnicity, sex, age, proportion of adults with a high school diploma, proportion of population not proficient in English, proportion of population living under poverty line, proportion of population with frequent mental and physical distress (14 or more self-reported days of mental or physical distress out of 30 days), and quartiles of mental health and primary care provider to population ratio at a US county level were extracted from 2021 County Health Rankings National Data collected by University of Wisconsin Population Health Institute. Data on access to broadband and technology enabled devices (PC, smartphone) were obtained from Social Determinants of Health Database (2018) aggregated by Agency for Healthcare Research and Quality (AHRQ). Percent of people per county that use the internet at broadband speed higher than 25 mbps per download was obtained from United States Broadband Usage Percentages Dataset collected by Microsoft in 2020. To estimate the cost for developing new broadband infrastructure for each county, data on percent of people with access to broadband, county land area (m^2) obtained from US County Land Area (2010) dataset, and estimated fixed cost for building broadband infrastructure per square mile ($27,000) calculated by Department of Transportation were used. Similarly, the estimated cost for subsidizing smartphones was calculated using percent of people with no smartphone, county population, and average selling price (ASP) of smartphones in 2021 were used. SQL Server was used to extract the markers from publicly available datasets and to calculate the estimated setup cost of broadband and technology enabled devices for each county.


Interactive dashboard was created using Tableau Public to map US counties and the disparities in access to mental health and primary care, telecommunications infrastructure, and the level of digital literacy based on demographic information. 


## Presentation
https://tinyurl.com/healthequity4you
