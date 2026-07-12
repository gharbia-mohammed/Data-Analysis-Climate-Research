# # Climate Data Analytics Project 

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tech Stack](#tech-stack)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Seasonality Analysis](#seasonality-analysis)
- [Key Findings](#key-findings)
- [Conclusion](#conclusion)


### Project Overview

This project analyzes the long-term climate variability in North Africa from 1941 to 2020 using the ERA5 reanalysis dataset. 
The project focuses on the three main meteorological variables that directly influence renewable energy systems and heat stress in desert environments:

- Temperature T(°c)
- Wind Speed (WS)
- Surface Downwelling Shortwave Radiation (SSRD)

The main objective is to understand how these variables evolved over eight decades and identify long-term trends and seasonal patterns using data analysis and visualization techniques.

### Data sources :

The  dataset used in this project is the ERA5 Reanalysis Dataset (ECMWF), which provides global coverage, 
hourly and monthly data, and a high spatial resolution of 0.25° × 0.25° for the period from 1940-2020. 
ERA5 is widely used in climate analysis due to its spatial consistency, long historical coverage, 
and high-quality integration of atmospheric observations.
ERA5 provides reliable historical climate records and is widely used for environmental and energy analysis.

### Tech stack :

### Programming & Analysis

- R
- ggplot2
- dplyr
- raster
- ncdf4
  
### Tasks Performed

- Data extraction
- Data cleaning
- Feature preparation
- Time-series analysis
- Seasonal analysis
- Statistical summaries
- Data visualization

### Data cleaning / preperation :

1. Loading and inspecting the ERA5 dataset
<br><br>
2. Selecting the North Africa domain
<br><br>
3. Handling missing values 
<br><br>
4. Calculating annual and monthly averages
<br><br>
5. Splitting the dataset into two reference periods:
1941–1980 & 1981–2020 .
<br><br>
6. Preparing time-series and climatological summaries


### Exploratoty Data analysis :

How has the mean temperature changed over 80 years?

What is the long-term behavior of wind speed?

How have temperature, wind speed, and solar radiation changed over time?

How do monthly climatological patterns differ between 1941–1980 vs 1981–2020?

Are there detectable seasonal trends?

The project includes:

1.Annual Time Series (1941–2020)

2.Seasonal Comparison between historical periods.

3.Climate indicators visualization.

4.Long-term trends for T(°c), WS, SSRD

### Seasonality Analysis

Seasonal patterns were analyzed for all climate variables to understand how climate conditions change throughout the year.
The analysis focuses on:

# Air Temperature T(°c)
Monthly temperature distribution.
Comparison between 1941–1980 and 1981–2020.
Identification of warming patterns across seasons.
# Wind Speed (WS)
Monthly wind variability.
Seasonal peaks and low-wind periods.
Changes between the two historical periods.
# Surface Solar Radiation (SSRD)
Seasonal behavior of solar radiation.
Monthly differences across decades.
Identification of periods with the highest solar potential.

Questions explored:

Which months experienced the strongest changes?
Did seasonal patterns remain stable over time?
Which variable shows the largest seasonal variation


## Key Findings

### 1.Temperature T(°c)

- Temperature increased from **21.25°C in 1943** to **24.8°C in 2020**, indicating a clear warming trend across North Africa.

<img width="600" height="300" alt="ta_plot" src="https://github.com/user-attachments/assets/85a35926-eed0-43a1-af66-8607824efadf" />

---

### 2. Wind Speed (WS)

- Wind speeds ranged from **1.65 to 2.7 m/s** over the study period.
- The highest values occurred in **1943** and **2000**, while the lowest values were recorded in **1958** and **1962**.
- 
<img width="600" height="300" alt="ws_plot" src="https://github.com/user-attachments/assets/ba35ee71-4452-499a-bae7-d437c53ad2ce" />

---

### 3. Solar Irradiance (SSRD)

- Annual solar irradiance ranged from **255.5 to 265 Wh/m²**.
- The highest values occurred in the early **1940s**, while the lowest values were observed in the **mid-1970s**.
- The overall trend shows a slight decline over the 80-year period.

<img width="600" height="300" alt="ssrd_plot" src="https://github.com/user-attachments/assets/d9a587b4-d32a-46b3-b277-2dc4c4b27a99" />

---

### 4. Monthly Temperature Climatology T(°c)

- Monthly temperatures were compared between **1941–1980** and **1981–2020**.
- Temperatures increased across all months during the recent period.
- Summer months (**June–August**) recorded the highest temperatures, while **January** and **February** remained the coolest months.
- The largest increase occurred in **July**, reaching approximately **1°C**, whereas the smallest change was observed in **February**.

<img width="600" height="300" alt="ta_monthly_comparison" src="https://github.com/user-attachments/assets/c3835c5c-8ed1-40bc-a5b9-268614de24c7" />

---

### 5. Monthly Wind Speed Climatology (WS)

- Monthly wind speed patterns were analyzed to identify seasonal variability.
- Wind speed showed only minor changes during summer months.
- More pronounced changes were observed during winter.
- The largest increase occurred in **October** and **December**, reaching approximately **0.2 m/s**.

<img width="600" height="300" alt="ws_monthly_comparison" src="https://github.com/user-attachments/assets/4dab5ff9-cf72-4d55-b4c7-1f7a245596a8" />

---

### 6. Monthly Solar Radiation Climatology (SSRD)

- Solar radiation exhibited a clear seasonal cycle.
- Peak values occurred between **May and July**, while the lowest values were observed during **December** and **January**.
- Solar radiation patterns remained largely stable between the two periods.
- Only a slight decrease was observed in **May**.

<img width="600" height="300" alt="ssrd_monthly_comparison" src="https://github.com/user-attachments/assets/a61a2e1e-7dc2-4fab-a727-e96b1eddbb58" />

## Conclusion

Using 80 years of climate data, this project applied time-series analysis, seasonal comparisons, and data visualization to identify long-term trends in North Africa.
The results show increasing temperatures, seasonal changes in wind speed, and relatively stable solar radiation patterns. These insights highlight the value of data analytics in understanding climate variability and supporting decisions in renewable energy and environmental planning.
