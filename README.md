# Harnessing Data for Bed Type Usage Forecasting Future Demand

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Workflow](#workflow)
4. [Usage](#usage)
5. [Prerequisites](#prerequisites)
6. [Visualization](#visualization)
7. [Author](#author)

## Overview
This project focuses on analyzing the usage of bed types from existing hospital admission data, visualizing the patterns, and forecasting the future demand for different types of beds required by the hospital. By utilizing data analysis techniques and visualizations, it provides actionable insights for hospital resource management.

## Features
- Visualization of missing data using heatmaps.
- Cleaning and formatting hospital admission data.
- Conversion of date fields into structured formats for analysis.
- Extraction of monthly and yearly trends from admission data.
- Forecasting future demand for hospital bed types.
- Productive and effective visualizations for actionable insights.

## Workflow
1. **Libraries Used**:
   - `numpy`
   - `pandas`
   - `matplotlib`
   - `seaborn`

2. **Dataset**:
   - The analysis revolves around a CSV file containing hospital admission data (`E:/ip_Admission 22-25.csv`).

3. **Steps in the Notebook**:
   - Importing necessary libraries.
   - Loading and previewing the dataset.
   - Handling missing data visualized through `seaborn` heatmaps.
   - Transforming date fields into structured formats (`yyyy-mm-dd`).
   - Forecasting demand for different bed types.
   - Saving the cleaned and formatted data into new CSV files:
     - `hospital_data_formatted.csv`
     - `hospital_data_month_year.csv`

4. **Key Outputs**:
   - Heatmaps showcasing missing data patterns.
   - Data tables with enriched features like month and year columns.
   - Forecasted trends for future bed type demands.

## Usage
To use or extend the code:
- Modify the paths to the dataset as per your environment.
- Install the required libraries using `pip install numpy pandas matplotlib seaborn`.
- Run the notebook sequentially to reproduce the results.

## Prerequisites
- Python 3.11.1
- Jupyter Notebook or any IDE supporting `.ipynb` files.

## Visualization
The project includes productive and effective visualizations, such as:
- Heatmaps for missing data patterns.
- Tabular views of transformed datasets.
- Forecasted trends for hospital bed type usage.
- Visual hierarchy and appropriate chart types to highlight insights.
- Use of color schemes to make visualizations intuitive and engaging.

## Author
This project is part of the `bed-type-projection` repository created by [**abhinay1249**](https://github.com/abhinay1249?tab=repositories).

## Contact
Feel free to connect for feedback or collaboration.  
 - abhinaymarise@gmail.com
 - [LinkedIn](https://www.linkedin.com/in/abhinay-marise-34b648273/)
