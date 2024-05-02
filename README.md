# Datetime-Data-Analysis
# Chicago Crime Data Visualization

## Overview

This project utilizes Chicago crime data to perform data visualization and analysis. The dataset contains information about various crime incidents, including the type of crime, location, and time. The aim is to explore trends, patterns, and seasonality in crime occurrences over the years.

---

## Data Loading and Inspection

The project starts by loading and inspecting the Chicago crime dataset. The dataset is sourced from multiple CSV files stored in a specified folder path. After concatenating the files, the data is examined for its structure, including columns, data types, and missing values.

### Data Dictionary

The dataset includes the following columns:

- `ID`: Unique identifier for each crime incident.
- `Date`: Date and time of the crime.
- `Primary Type`: Type of crime.
- `Description`: Description of the crime.
- `Location Description`: Description of the location where the crime occurred.
- `Arrest`: Boolean indicating whether an arrest was made.
- `Domestic`: Boolean indicating whether the crime involved domestic violence.
- `Beat`: Police beat where the crime occurred.
- `District`: Police district where the crime occurred.
- `Ward`: Ward where the crime occurred.
- `Latitude`: Latitude coordinate of the crime location.
- `Longitude`: Longitude coordinate of the crime location.

---

## Data Preprocessing

The data preprocessing steps involve converting the `Date` column to datetime format, handling missing values, and setting the index to the datetime column for time-series analysis. Additionally, the dataset is sorted based on the date.

---

## Exploratory Data Analysis (EDA)

### Crime by Year

The analysis examines the total number of crimes reported each year. A trend analysis is performed to identify any changes in crime occurrence over time. The findings reveal a steady decrease in total crime from 2001 to 2021, with a slight increase observed in 2022.

### Crime by Type

The project investigates individual crime types over the years. A breakdown of crime occurrences by type provides insights into the distribution and trends of specific criminal activities.

### Seasonality Analysis

A seasonality analysis is conducted to identify cyclic patterns in crime occurrences. Seasonal decomposition techniques are applied to detect periodic fluctuations in crime data. The analysis reveals a yearly cycle with a period of 365 days and a fluctuation of approximately 8897.74 crimes per month.

---

## Conclusion

The project showcases the utilization of Chicago crime data for data visualization and analysis. By exploring trends, patterns, and seasonality in crime occurrences, valuable insights are gained into the dynamics of criminal activities over the years.

