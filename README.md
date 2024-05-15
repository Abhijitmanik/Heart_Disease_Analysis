# Heartdisease  Data Analysis



## Overview

This repository contains code and data for analyzing heart disease data using pandas and seaborn. The goal of this analysis is to explore various factors related to heart disease and visualize the relationships between these factors.

## Dataset Description

The dataset used in this project contains the following columns:

- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **ChestPainType**: Type of chest pain experienced
- **RestingBP**: Resting blood pressure
- **Cholesterol**: Cholesterol level
- **FastingBS**: Fasting blood sugar (1 if > 120 mg/dl, 0 otherwise)
- **RestingECG**: Resting electrocardiographic results
- **MaxHR**: Maximum heart rate achieved
- **ExerciseAngina**: Exercise-induced angina (1 = yes, 0 = no)
- **Oldpeak**: ST depression induced by exercise relative to rest
- **ST_Slope**: Slope of the peak exercise ST segment
- **HeartDisease**: Presence of heart disease (1 = yes, 0 = no)

## Analysis

The analysis was performed using Python libraries such as pandas and seaborn. Some of the key findings from the analysis include:

- Distribution of age among patients
- Relationship between gender and heart disease
- Impact of different types of chest pain on heart disease
- Correlation between various medical metrics and heart disease
- Visualizations to understand the distribution and relationships between variables

## Files

- `heart_disease_dataset.csv`: The dataset in CSV format.
- `heart_disease_analysis.ipynb`: Jupyter Notebook containing the Python code for data analysis.
- `heart_disease_analysis.html`: HTML version of the Jupyter Notebook for easier viewing.

## Requirements

- Python 3.x
- pandas
- seaborn
- Jupyter Notebook (optional for viewing the analysis)

## Conclusion
The analysis provides valuable insights into the factors influencing heart disease. Further analysis and machine learning models can be developed based on this dataset to predict heart disease or target specific patient segments.
