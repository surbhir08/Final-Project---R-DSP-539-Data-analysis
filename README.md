# Final-Project---R-DSP-539-Data-analysis

# Covid 19 Data Analysis usinf R Language

# Dataset used: (Data set is allowed to use for project analysis purposes)
confirmedraw <- read.csv("https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv")

deathsraw <- read.csv("https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv")

recoveredraw <- read.csv("https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv")

# Library required:

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

Analysis is done using linear model, SIR model, Regression tree followed by pruning and use of cross validation and boosting.

Informative output along with plots and summary included in PDF file: FinalProjectCovidDataAnalysisR

# An additional R markdown file is available in the repository which shows usage of Covid.Analytics package.
# Python code for graphical representation of data is added too in the repository.

Disclaimer: The work is by a student and analysis may not be appropriate.
