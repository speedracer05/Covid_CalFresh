# Charting Covid-19 Impact to California's Food Assistance Program (SNAP)

## Project Proposal
For our team project, we wanted to understand if usage of California's CalFresh program surged as a result of increased COVID-19 infection rates. CalFresh is California's implementation of the Federal Supplemental Nutrition Assistance Program, which provides food benefits to help people purchase food at teh grocery store. We'll take a look how COVID affected various counties and the relationship of COVID to employment, population and usage of CalFresh benefits.

###### Scope
Key assumption: As Covid infection rates increased, so did usage of CalFresh benefits
* Geographic coverage: California
* Timeframe: January 2020 through February 2021

###### Key Questions
The team wrote out a list of questions that we wanted to seek from the data.
*  What the 10 counties with the highest infection rates?
*  What was the worst affected county?
*  What was the least affected county?
*  What is the relationship between rural and urban infection rates?
*  What are the worst covid infection rates as a percentage of population? Are the counties rural, urban, or mixed?
*  Show the correlation between COVID-19 infection rates and CalFresh usage

###### Possible Sources for Data
We needed to find data that would provide infection rates, population, unemployment, CalFresh information. Additionally, the data had to be available by year, month, state, and county. There was no single source for the information, so we investigate several sources. 
1. https://www.cdss.ca.gov/inforesources/research-and-data/calfresh-data-tables/dfa256
1. https://data.nal.usda.gov/dataset/supplemental-nutrition-assistance-program-snap-data-system
1. https://data.ca.gov/en/dataset?res_format=CSV&organization=california-employment-development-department
1. https://data.ca.gov/group/covid-19
1. https://www.fns.usda.gov/pd/supplemental-nutrition-assistance-program-snap
1. https://github.com/nytimes/covid-19-data
1. https://covidtracking.com/
1. https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-total.html

After examining several datasets, we settled on three. Subsquently, we discovered that there was A LOT of data munging and clean up that had to happen in order to make it usable.  
1. CalFresh. https://www.cdss.ca.gov/inforesources/research-and-data/calfresh-data-tables/dfa256
1. US_Counties. https://github.com/nytimes/covid-19-data
1. US Census. https://www.census.gov/data/datasets/time-series/demo/popest/2010s-counties-total.html


## Key Takeaway
We found that COVID-19, initially did not have a direct impact on CalFresh usage. Rather, goverment containment policies, which created a massive spike in unemployment, primarily contributed to the marked increase of CalFresh usage. In fact, CalFresh usage increased with unemployment and decreased in sympathy with declining unemployment. It was only after the second-wave of infections, in the fall of 2020, that we see a direct correlation between CalFresh benefit usage and COVID cases.

## Built With
* Jupyter notebook Code Version: 6.0.3
Chrome: 87.0.4280.141
Node.js: 12.18.3
OS: Windows_NT x64 10.0.19042
* conda 4.10.0
* Python 3.6.10 :: Anaconda, Inc.
* Kite Pro Version: 1.2021.310.0
## Contributing
* DeJuan Hall
* Jackson Freese
* Siddharth Das

## Author
* John Chan

## Acknowledgments
* DeJuan did a great job in cleaning up one of the datasets, was instrumental for the other team members.
