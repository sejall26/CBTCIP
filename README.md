## Project Overview
This repository contains two data science projects: **Iris Flower Classification** and **Unemployment Analysis in India**. The Iris classification project aims to classify iris flowers into species based on their physical characteristics, while This project aims to analyze unemployment trends in India. The analysis includes a comparison of unemployment rates before and after the lockdown, utilizing various data visualization techniques to provide insights into the impact of the lockdown on employment across different states.

## Iris Flower Classification

### Dataset
The Iris dataset is a classic dataset in machine learning, containing information about three species of iris flowers (Setosa, Versicolor, and Virginica) with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Features
- **Data Exploration**: Visualizations to understand the data distribution and relationships between features.
- **Model Training**: Implementation of various classification algorithms (e.g., Logistic Regression, Decision Trees, SVM).
- **Model Evaluation**: Accuracy evaluation of different algorithm using graph for model performance assessment.

### Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


## Unemployment Analysis in India

### Dataset
The unemployment analysis dataset provides detailed insights into unemployment rates across different regions in India. The dataset includes the following features:

- **Region**: The name of the state or union territory in India where the data was collected.
- **Date**: The date on which the unemployment data was recorded, indicating the specific time frame of the analysis.
- **Frequency**: The frequency of the data collection (e.g., monthly, quarterly, annually), which indicates how often the data is updated.
- **Estimated Unemployment Rate (%)**: The percentage of the labor force that is unemployed but actively seeking employment within the specified region and time frame.
- **Estimated Employed**: The estimated number of individuals employed in the region, providing insight into the size of the workforce.
- **Estimated Labour Participation Rate (%)**: The percentage of the working-age population that is either employed or actively looking for work, reflecting the overall engagement of individuals in the labor market.
- **Longitude**: The geographical coordinate representing the east-west position of the region, useful for mapping and spatial analysis.
- **Latitude**: The geographical coordinate representing the north-south position of the region, also useful for mapping and spatial analysis.


## Features

- **Data Filtering**: Analyzes unemployment data before and after the lockdown (months 1-4 and 4-7).
- **Statistical Analysis**: Computes mean unemployment rates by state and calculates percentage changes.
- **Data Visualization**: Includes various plots such as bar charts, box plots, and geospatial scatter plots to visually represent data.
- **Interactive Visuals**: Utilizes Plotly for interactive graphs, enabling users to explore data dynamically.

## Technologies Used
- Python
- Pandas
- NumPy
- Plotly Express
- Seaborn
- Jupyter Notebook
