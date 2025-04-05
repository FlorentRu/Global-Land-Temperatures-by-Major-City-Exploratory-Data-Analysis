# Global Land Temperatures by Major City Exploratory Data Analysis

This repository contains an exploratory data analysis (EDA) of the GlobalLandTemperaturesByMajorCity dataset. The project demonstrates how to load, clean, and visualize climate data, with the goal of uncovering trends, seasonal patterns, and possible evidence of climate change impacts in various urban centers around the globe.

Dataset Description
The dataset, originally sourced from Kaggle, provides historical temperature records for major cities worldwide. It includes:

- dt: Date of the temperature recording, monthly intervals.

- AverageTemperature: Observed mean temperature for that month.

- AverageTemperatureUncertainty: 95% confidence interval around the mean.

- City: Major city name.

- Country: Country name.

- Latitude and Longitude: Geographic coordinates of the city.

### Project Objectives

1- Data Wrangling: Load the CSV data, inspect structure, and handle missing values.

2- Descriptive Statistics: Calculate summary metrics (mean, median, min, max) for the main variables.

3- Visualization: Create a suite of plots such as histograms, time series, boxplots, bar charts, heatmaps to reveal:

- Long-term temperature trends by city or country.

- Seasonal variability in temperatures.

- Geographic differences in mean or median temperatures.

4- Discussion of Findings: Develop questions about climate change and highlight areas for further research.

### Repository Structure

- data/: Contains the original dataset and any other data files used in the project.

- R/: Houses R scripts for loading, cleaning, transforming, and modeling the data.

- reports/: Contains R Markdown files or similar notebooks that generate visualizations and analyses.

- images/: Stores the exported plots/visualizations.

### Visualizations

1- Histogram of Average Temperatures
Shows the overall distribution and highlights any skewness or outliers.

2- Time Series (Single City)
Plots historical temperature trends (e.g., for London) to identify long-term warming or seasonal cycles.

3- Boxplot by City
Compares the temperature distributions for a subset of cities with the highest record counts.

4- Bar Chart of Mean Temperatures by Country
Ranks countries by their average temperature to spot the warmest or coolest regions.

5- Seasonal Boxplots by Month
Visualizes temperature patterns month by month, capturing seasonality across multiple years.

6- Heatmap of Monthly Averages
Displays an annual-by-month grid of temperatures, highlighting seasonal shifts and possible warming trends.

### Based the visualizations here are some example questions and insights

- Are some cities experiencing faster warming than others?
Time series plots may show steeper temperature increases for certain locations.

- Has the distribution of temperatures shifted over time?
Comparing historical subsets can reveal upward shifts or more frequent extreme events.

- Which months are warming the most?
Seasonal boxplots or heatmaps can detect if summers or winters are changing more rapidly.

- How do regional differences factor into climate change impacts?
Bar charts by country and boxplots by city show large geographic disparities in mean temperatures.

## Potentiel next steps I can take:

- Statistical Modeling: Fit linear or time-series models to quantify warming rates more precisely.

- Geospatial Analysis: Map geographic temperature patterns and integrate with other climate datasets.

- Feature Engineering: Create additional climate indicators such as temperature anomalies, heatwave frequency.

- Dashboard Integration: Build an interactive tool such as Shiny app to explore temperature trends dynamically.

