# Zuber Rides Analysis

<p align="center">
  <img src="https://github.com/kellyshreeve/Zuber_Rides_Analysis/blob/main/images/carimage.png" 
  alt="Purple car cartoon">
</p>

# Project Overview

This repository hosts a data science project for Zuber, a new ride share company launching in Chicago. It is an in-depth analysis of customer behvior in the area and includes descriptive statistics, data visualizations, and hypothesis tests on data from competitors in the area.

# Installation and Setup

## Codes and Resources Used

  - <b>Editor Used</b>: Visual Studio Code
  - <b>Python Version</b>: 3.10.9

## Python Packages Used

  - <b>General Purpose</b>: NA
  - <b>Data Manipulation</b>: ```pandas```
  - <b>Data Visualization</b>: ```plotly.express```
  - <b>Statistical Analysis</b>: ```SciPy, researchpy```
  - <b>Machine Learning</b>: NA

## Installing development requirements

```pip install -r requirements.txt```

# Data

## Source Data

There are three source datasets: 
  1. Local ride share companies and their total number of trips (n=64)
  2. Local neighborhoods and their average number of drop offs (n=94)
  3. Ride share trips with start time, weather, and duration (n=1068)

## Data Acquisition

The data were retrieved through HTML parsing a web page and SQL queries of a large database provided by TripleTen. Data were downloaded into csvs, and then uploaded into Python for analysis. 

## Data Preprocessing

Data were checked for missing values and duplicates. None were found and no imputation was necessary.
 
# Code Structure
```
  ├── LICENSE
  ├── README.md          
  ├── data
  │   ├── sql_result_01.csv      
  │   ├── sql_result_04.csv       
  │   └── sql_result_07.csv 
  │
  ├── images
  │   └── car-picture.png    
  │
  ├── notebooks  
  │   └── Zuber_Analysis.ipynb 
  │
  └── requirements.txt  
```

# Results and Evaluation

# Future Work

# Acknowledgments/References
