# Weather & Crime Analysis (R)

This project analyses the relationship between **weather patterns** and **crime incidents** using real-world datasets.  
It was created as part of my MA304 Data Analysis coursework and demonstrates skills in **data cleaning, merging, time-series analysis, correlation analysis, and visualisation in R**.

---

##  Project Summary

- Cleaned and merged weather and crime datasets (2023–2025)
- Performed **time-series analysis** to identify crime seasonality
- Examined relationships between **temperature, rainfall, and crime frequency**
- Created visualisations using **ggplot2**
- Produced an analytical report in **RMarkdown**

---

##  Techniques Used

- Data cleaning & preprocessing (tidyverse)
- Parsing and working with dates (lubridate)
- SQL-style joins in R
- Correlation analysis
- Grouping, aggregation, and trend detection
- Visualisation with ggplot2

---

##  Key Findings

- Crime levels show clear **seasonal trends** (higher in warm months)
- Temperature has a **positive correlation** with crime activity
- Rainfall tends to slightly **decrease** crime incidents
- Combined time-series charts show weather-driven behaviour patterns

---

##  Repository Structure
/data
weather_sample.csv
crime_sample.csv

/notebooks
weather_crime_analysis.Rmd

/results
crime_by_month.png
temperature_vs_crime.png
rainfall_vs_crime.png
correlation_matrix.png
combined_timeseries.png

---

##  How to Run

```r
install.packages(c("tidyverse", "ggplot2", "lubridate"))
rmarkdown::render("notebooks/weather_crime_analysis.Rmd")
