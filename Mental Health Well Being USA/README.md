## Installation

To run this code you need to install following libraries: pandas, numpy , urllib, matplotlib , plotly , sklearn, statsmodels. Use the following command to start the installation.

```bash
pip install <package name here>
```

## Project Description

Aim of this project is to: 

1. Compare and predict mental health among different states in the US for years 2015 - 2020. 
2. Describe how mental health differs across different counties and regions in US. 
3. Provide an easy solution for scraping health dataset that can be easly modified for other years and attributes.

Data used for this project is retrieved from [County Health Ranks](https://www.countyhealthrankings.org/) program, which as main data source has [Behavioral Risk Factor Surveillance System (BRFSS)](https://www.cdc.gov/brfss/questionnaires/index.htm) - nation's premier system of health-related telephone survey. 


## Files Description

- *health_data_scraping.ipynb* - downloads, reads and cleans data files for years 2015 - 2020 from County Health Ranks program.
- *EDA.ipynb* - Visualizes the data via line charts, density plot, box plots and choropleths.
- *modeling.ipynb* - Compares different machine learning models for predicting mental health at state level. 


## Acknowledgments

Data was scraped from [County Health Ranks](https://www.countyhealthrankings.org/) website.