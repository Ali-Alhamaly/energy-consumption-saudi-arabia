# Saudi Arabia energy consumption data exploration

This small project is concerned with data exploration and analysis of Saudi Arabia energy consumption pattern. I explore energy consumption patterns throughout the years and comment on the large growth of energy consumption. 

## Installation

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.
actually only ```urllib, json, pandas, numpy, matplotlib``` libraries have been used in this project.

## Project Motivation

my motivation behind this small project is to understand primary energy consumption of Saudi Arabia. to be specific, I'm interested in answering the below questions: 

1. What are the main primary energy sources used in Saudi Arabia? and how much each source contributes to the total primary energy of the country?
2. How much is the growth of energy consumption in Saudi Arabia throughout the years?
3. How is the energy intensity of Saudi Arabia changing? in other words, How is the country doing in terms of energy efficiency?
4. How is electricity consumption patterns in specific compared with the total primary energy of the country?

## File Descriptions

The jupyter notebook available here contains the data analysis used to answer the above questions.  in addition, the three ```csv``` files contain electricity data used in the analysis. These files were obtained from  [KAPSARC](https://datasource.kapsarc.org/pages/home/).  the links to these data files can be found in ```sources.txt``` file.
	
## Results

the main findings of the code can be found at the Meduim post available [here](https://medium.com/@hamalyas_/this-is-how-saudi-arabia-energy-consumption-is-growing-33281c7dd737).

## Licensing, Authors, Acknowledgements

the data used in this project were obtained from two sources: 

1. U.S. Energy Information Administration (EIA) [International Energy Data ] (https://www.eia.gov/opendata/qb.php?category=2134384)
2. King Abdullah Petroleum Studies and Research Center [KAPSARC](https://datasource.kapsarc.org/pages/home/)

EIA data was downloaded through their API. links to the data sets are included in the main notebook. 