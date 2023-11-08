# WTAlogisticreg
Logistic regression tutorial to predict Women's Tennis Association match outcomes.

Author: Emma L Davis

Date: Nov 2023

### System requirements

+ R version 4.2.2 or later

+ Installation of the `tidyverse` package

### Data 

Raw data files are split by year and come from http://www.tennis-data.co.uk/alldata.phpD (accessed 31-10-2023). These have then been cleaned (using file `DataCleaning.Rmd`) and collated to give two main data files:

+ Data for fitting (20,912 matches) `data/WTAFittingData.csv`

+ Data for testing (2,316 matches) `data/WTATestingData.csv`

### Tutorial 

The full tutorial is provided in the R Markdown file `LogisticRegTutorial.Rmd` and associated html output file `LogisticRegTutorial.html`.
