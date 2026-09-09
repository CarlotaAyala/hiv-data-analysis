# 🩺 HIV/AIDS Data Analysis & Visualization

Exploratory data analysis and interactive visualization of global **HIV/AIDS data**, developed in **R**.

This project explores the evolution and impact of HIV/AIDS across countries and regions through data analysis and visual storytelling, with the aim of identifying patterns, trends and relationships between different health and socioeconomic indicators.

---

## 🎯 Project Overview

The project combines data from multiple sources to study HIV/AIDS from different perspectives, using exploratory analysis, statistical techniques and interactive visualizations.

The analysis was developed as part of the **Exploratory Data Analysis and Visualization (AEDV)** course of the Data Science and Engineering degree at the **University of Las Palmas de Gran Canaria (ULPGC)**.

---

## 🔎 What does this project analyze?

The analysis focuses on several dimensions of the HIV/AIDS epidemic, including:

- Evolution of HIV/AIDS cases and deaths over time.
- Differences between countries, regions and income groups.
- Relationship between HIV/AIDS mortality and life expectancy.
- Analysis of new HIV infections and age-related patterns.
- Impact of health expenditure and access to treatment.
- Study of children orphaned due to AIDS.
- Correlation analysis between health and socioeconomic indicators.
- Dimensionality reduction using **Principal Component Analysis (PCA)**.
- Temporal analysis and forecasting.
- Interactive geographical and temporal visualizations.

---

## 📊 Main Components

### 📈 Exploratory Data Analysis

The main analysis is developed in:

`Proyecto.Rmd`

It includes data cleaning, transformation, exploratory analysis, statistical techniques and different types of visualizations to understand the evolution and impact of HIV/AIDS worldwide.

### 🖥️ Interactive Dashboard

An interactive dashboard was also developed in:

`ProyectoDashboard.Rmd`

The dashboard allows users to explore different indicators and visualizations dynamically, providing a more interactive way of understanding the data.

---

## 🛠️ Technologies Used

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![RStudio](https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=rstudio&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)

### Main R libraries

- `ggplot2`
- `dplyr`
- `tidyverse`
- `plotly`
- `leaflet`
- `highcharter`
- `shiny`
- `shinydashboard`
- `fpp3`
- `fable`
- `feasts`
- `tsibble`
- `GGally`
- `RColorBrewer`
- `patchwork`
- `openxlsx`
- `geojsonio`
- `wordcloud`
- `scales`

---

## 📂 Project Structure

```text
hiv-data-analysis/
│
├── Proyecto.Rmd
├── ProyectoDashboard.Rmd
├── Proyecto.html
│
├── annual-number-of-deaths-by-cause.xlsx
├── API_SP.POP.TOTL_DS2_es_excel_v2_4145.xlsx
├── CLASS.xlsx
├── country.clasification.xlsx
├── data.csv
├── deaths-from-hiv-by-age.xlsx
├── health-expenditure-and-financing-per-capita (1).csv
├── life-expectancy.xlsx
├── new-cases-of-hiv-infection.xlsx
├── number-of-children-orphaned-from-aids.csv
├── number-of-deaths-from-hivaids-who.csv
├── number-of-new-hiv-child-infections-vs-number-of-infections-averted-due-to-pmtct (1).csv
│
├── custom.css
├── estilos.css
├── img1.png
│
└── www/
    └── img2.jpg

## 📚 Data Sources

The project integrates multiple datasets containing information related to:

- HIV/AIDS deaths.
- New HIV infections.
- Population.
- Life expectancy.
- Health expenditure.
- HIV infections by age.
- Children orphaned due to AIDS.
- Prevention of mother-to-child transmission.
- Country and income classifications.

These datasets are combined to provide a broader view of the social and health impact of HIV/AIDS across different countries and regions.

---

## 📈 Analysis & Visualization

Different visualization techniques are used throughout the project, including:

- Time-series plots.
- Interactive charts.
- Geographical maps.
- Comparative plots between countries and regions.
- Correlation analysis.
- Principal Component Analysis.
- Forecasting and temporal analysis.
- Interactive dashboard components.

The use of interactive libraries such as **Plotly**, **Leaflet** and **Highcharter** makes it possible to explore the data from different perspectives.

---

## 🎓 Academic Context

This project was developed as part of the **Exploratory Data Analysis and Visualization (AEDV)** course in the **Data Science and Engineering** degree at ULPGC.

The main objective was to apply data exploration, visualization and statistical analysis techniques to a real-world dataset and communicate the results through meaningful visualizations.
