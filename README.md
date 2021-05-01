### Covid 19 Data Analysis usinf R Language

### Dataset used: (Data set is allowed to use for project analysis purposes)

confirmedraw <- read.csv("https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv")

deathsraw <- read.csv("https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv")

recoveredraw <- read.csv("https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv")

### Libraries required:
library(dplyr)
library(tinytex)
library(ggplot2)
library(ggplot2)
library(tmap)
library(deSolve)
library(date)
library(moderndive)
library(modelr)
library(dplyr)
library(sf)
require(tree)
library(MASS)})


### Files in the Repo:
1. **FinalProjectDataAnalysisR.Rmd** : Main project Analysis code in r markdown.
  The project contains covid analysis based on contry level and world level reports followed by prediction models like SIR, Regression trees.
  The final report of this project is explained in **FinalProjectReport.pdf file**.
  
2. **Python_CovidData.ipynb** : It's a raw notebook containing few analysis steps done in python just to explore the functions in python as well.

3. **covidAnalytics.Rmd** : This file contains a few analysis done using covid.analytics package. It was part of trial for my project. I wanted to explore different results.


### Disclaimer: The work is for a project and analysis may/may not be appropriate.
