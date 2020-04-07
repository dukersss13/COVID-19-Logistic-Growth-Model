# COVID-19 Model

# Abstract
The following model uses Logistic Growth to model the trend of the novel COVID-19 pandemic. It is assumed that with cautionary measures, human intervention and the recovered/removed population cannot carry or infect others, the pandemic will eventually approach a Carrying Capacity thus causing the infection rate to taper. 
The model is a work in progress. More updates and modifications will be added.

# Data
Main data sets are from the CSSE (John Hopkins University). A set of data will contain global confirmed cases and deaths. The other will be consisted of confirmed and deaths cases in the U.S. These data sets are updated daily at 12 A.M ET.

Sources: https://github.com/CSSEGISandData/COVID-19

# Description
The model is consisted of four main functions:
The first function cleans and extracts cases from the United States.
The second is the Logistic Growth function/equation.
The third uses the outputs from the first two functions and runs the logistic computation. 
The fourth is a main menu function that allows the user to select which country/region they would like to analyze.
Please make sure your spellings of countries/states/provinces are correct in order for the menu to work. 

Refer to the list of country names or states if needed. 

(Number of infections implies the number of confirmed cases ONLY).
The outputs are:

The current infected population.

The current mortality rate.

The date with the highest infection rate.

The estimated carrying capacity.

The expected number of new cases for the following day.

The estimated number of new deaths for the following day.

The logistic growth plot.

The date with peak infections.

The estimated number of deaths by the end date.

The estimated mortality rate by the end date.

*Note: Certain countries/regions/states will not have sufficient data for the algorithm to fully run. 
