# Data Analysis Climate Research

## Table of contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning / Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results / Findings](#results--findings)
- [Recommendations](#recommendations)


### Project Overview

This project analyzes the long-term climate variability in North Africa from 1941 to 2020 using the ERA5 reanalysis dataset. 
The study focuses on the three main meteorological variables that directly influence renewable energy systems and heat stress in desert environments:

Air Temperature (TAS) , Wind Speed (WS) , Surface Downwelling Shortwave Radiation (RSDS)
The goal is to investigate how these variables have changed over the last eight decades 
and identify key temporal patterns that describe North Africa’s climate change.


### Data sources :

The  dataset used in this project is the ERA5 Reanalysis Dataset (ECMWF), which provides global coverage, 
hourly and monthly data, and a high spatial resolution of 0.25° × 0.25° for the period from 1940 to 2020. 
ERA5 is widely used in climate analysis due to its spatial consistency, long historical coverage, 
and high-quality integration of atmospheric observations.

### Tools Used :
R Programming Language

Data Extraction (Extracting ERA5 climate variables)
Data Cleaning & Preprocessing
Time-Series Analysis
Statistical Summaries
Climatological Calculations (monthly/annual means,  trends)
Data Visualization (ggplot2 for time-series and monthly climatology plots)



### Data cleaning / preperation :

1.Loading and inspecting the ERA5 dataset
2.Selecting the North Africa domain
3.Handling missing values (rare in ERA5)
4.Computing annual and monthly averages
5.Splitting the dataset into two reference periods:
1941–1980 & 1981–2020 
7.Preparing time-series and climatological summaries


### Exploratoty Data analysis :

How has the mean temperature changed over 80 years?

What is the long-term behavior of wind speed?

Is solar irradiance decreasing or stable over time?

How do monthly climatological patterns differ between 1941–1980 vs 1981–2020?

Are there detectable seasonal trends?

Three main analyses were conducted:

1.Annual Time Series (1941–2020)

2.Seasonal / Monthly Climatology 

3.Long-term trends for TAS, WS, RSDS

### Results:

1. Air Temperature (TAS)

Temperature increased from 21.25°C in 1943 to 24.8°C in 2020.


<img width="750" height="450" alt="ta_plot" src="https://github.com/user-attachments/assets/89e22cb5-3def-49d7-9956-558e4c07bb20" />



2. Wind Speed (WS)

Wind speeds range from 1.65 to 2.7 m/s over the entire period.

Highest values occurred in 1943 and 2000; lowest in 1958 and 1962.

<img width="750" height="450" alt="ws_plot" src="https://github.com/user-attachments/assets/67bfee22-078a-4c55-ac30-ea442edb1229" />


3. Solar Irradiance (RSDS)

Values range from 255.5 to 265 Wh/m² annually.

Highest values in early 1940s, lowest in mid-1970s.

Overall trend shows a slight decline over the 80-year period.


<img width="750" height="450" alt="ssrd_plot" src="https://github.com/user-attachments/assets/fd0d6dfb-7175-4995-bf41-83df2a9e942a" />


### conclusion:

This historical climate assessment reveals that:

Temperature shows a strong upward trend.

Wind speed varies substantially, with increases in winter months.

Solar irradiance remains largely stable, showing only small long-term reductions.

These findings highlight the importance of understanding long-term climate behavior in North Africa,
especially in regions dependent on climate-sensitive sectors such as agriculture, water resources, and renewable energy.

