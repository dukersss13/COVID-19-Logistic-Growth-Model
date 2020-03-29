# COVID-19 U.S Model

# Abstract
The following model uses Logistic Growth to model the trend of the novel COVID-19 pandemic in the United States. The main assumption made is human intervention. It is assumed that with cautionary measures and human intervention, the pandemic will eventually approach a Carrying Capacity thus leading the infection rate to tail off. 

# Data
Main data sets are extracted from the World Health Organization. They are csv files of Confirmed, Deaths and Recovered cases around the world. For this particular model, I will be only looking at U.S cases.

# Description
The model is consisted of three main functions:
The first function cleans and extracts cases from the United States.
The second is the Logistic Growth function/equation.
The third uses the outputs from the first two functions and does the computations. 

The outputs are:
The current mortality rate.
The date with the highest infection rate.
The estimated carrying capacity.
The total number of infections for the following day.
The expected number of deaths for the following day.

The logistic growth plot.

The expected end date.
The expected number of deaths by that date.
The expected mortality rate by that date.