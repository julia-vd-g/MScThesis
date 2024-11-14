# Using AI/ML to identify propagation characteristics of European heatwaves

This repository contains the code used during the masters thesis for the master Statistics and Data Science. During the thesis propagation characteristics of European heatwaves have been studied with the aim of defining sources and sinks. To this extend, complex network variables have been used. In order to explore the definitions as well as their generalizability to the climatological period of 1990 to 2020, ML methods were used. 
Withing this repository, the usage of these ML methods is shown as well as some visualizations representing the process of defining sources and sinks as well as their results.

## The files within this repo
The code folder contains all the necessary files to reproduce the project.
- data_prep: Conatins the steps taken to pre-process the raw NetCDF4 files into Pandas dataframes leter to be used in the analysis.
- unsupervised: Contains the exploration steps of the defined definitions for sources and sinks. A one-class SVM was implemented to explore the models ability to clearly distinguish between sources and sinks.
- supervised: Contains the steps taken to explore what ML methods are able to classify the data and test their generalizability to the entire climatological period.

The visualizations forlder contains a file (geo_vis) used to visualize the source and sink results, where the data folder contains the necessary files to plot NUTS lines.

Lastly, the data used for this project can be found at: https://doi.org/10.4121/765bc025-80d2-4a91-a59c-1842ebfbbfce.v1 
