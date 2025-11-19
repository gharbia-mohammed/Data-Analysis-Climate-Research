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
and identify key temporal patterns that describe North Africa’s climate evolution.


### Data sources :

The primary dataset used in this project is  ERA5 Reanalysis Dataset (ECMWF) which is :
Global coverage, Hourly & monthly data and High spatial resolution (0.25° × 0.25°)
for period from 1940 to 2020. ERA5 is widely used in climate analysis due to its spatial consistency, 
long historical coverage, and high-quality assimilation of atmospheric observations.


### Tools Used :
R Programming Language

Data Loading (reading ERA5 climate variables)
Data Cleaning & Preprocessing
Time-Series Analysis
Statistical Summaries
Climatological Calculations (monthly/annual means,  trends)
Data Visualization (ggplot2 for time-series and monthly climatology plots)



### Data cleaning / preperation :

1.Loading and inspecting the ERA5 dataset
2.Selecting the North Africa domain
3.Converting flux variables to monthly means
4.Handling missing values (rare in ERA5)
5.Computing annual and monthly averages
6.Splitting the dataset into two reference periods:
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

2.Seasonal / Monthly Climatology (two periods)

3.Long-term trends for TAS, WS, RSDS

### Results:

1. Air Temperature (TAS)

Temperature increased from ~21.25°C in 1943 to ~24.8°C in 2020.

Summer months (June–July–August) show the strongest warming.

The largest monthly increase appears in July (~+1°C).

→ North Africa has experienced a consistent warming trend, especially in the last two decades.

2. Wind Speed (WS)

Wind speeds range from ~1.65 to 2.7 m/s over the entire period.

Highest values occurred in 1943 and 2000; lowest in 1958 and 1962.

Monthly comparison shows:

Summer winds show little change

Winter winds significantly increased, mainly in October and December (+1.15 m/s)

→ Wind speed exhibits strong interannual variability, with noticeable seasonal differences.

3. Solar Irradiance (RSDS)

Values range from ~255.5 to 265 Wh/m² annually.

Highest values in early 1940s, lowest in mid-1970s.

Overall trend shows a slight decline over the 80-year period.

Monthly patterns are stable across both periods, with only a minor decrease in May.

→ Solar irradiance remains highly stable across decades, with only slight long-term reductions.

### conclusion:

This historical climate assessment reveals that:

Temperature shows a strong upward trend, especially in summer months.

Wind speed varies substantially, with increases in winter months.

Solar irradiance remains largely stable, showing only small long-term reductions.

These findings highlight the importance of understanding long-term climate behavior in North Africa, especially in regions dependent on climate-sensitive sectors such as agriculture, water resources, and renewable energy.

High spatial resolution (~0.25° × 0.25°)

Period: 1940–present
