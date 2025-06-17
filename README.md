# COVID-19 Data Analysis and Predictive Modeling

## Overview
This project involves analyzing COVID-19 patient data to identify key risk factors, visualize trends over time, and develop predictive models for patient mortality. The goal is to support healthcare decision-making by providing actionable insights into patient outcomes.

## Objectives
- Clean and preprocess COVID-19 patient data
- Engineer relevant features such as age groups, comorbidities, and severity levels
- Perform exploratory data analysis (EDA) to uncover patterns and trends
- Visualize death trends over time
- Identify patient clusters based on health conditions
- Build and evaluate a logistic regression model to predict mortality risk

## Dataset
The dataset used in this project contains anonymized patient records, including demographic information, medical conditions, treatment indicators, and outcomes.
**Source:** Local COVID-19 dataset (`Covid Data.csv.zip`)

## Technologies & Libraries
- Python 3.x
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

## Methodology

### 1. Data Collection & Exploration
- Loaded and inspected data to understand structure and content
- Handled missing values
- Created new features such as age groups and severity indicators

### 2. Data Visualization
- Analyzed trends in death rates over time using rolling averages
- Visualized distributions of key variables (age, comorbidities, severity)

### 3. Clustering Analysis
- Applied KMeans clustering to identify patient segments based on features like age and comorbidity count

### 4. Predictive Modeling
- Selected core features (`AGE`, `COMORBIDITY_COUNT`, `SEVERE_CASE`, `HAS_COMORBIDITY`)
- Split data into training and testing sets
- Trained a logistic regression model to predict patient mortality (`DIED`)
- Evaluated model performance using classification metrics

## Results & Insights
- Key risk factors for mortality include advanced age, higher number of comorbidities, and severe cases
- Patient clustering reveals segments that can benefit from targeted interventions
- The logistic regression provides a baseline model for mortality risk prediction

## Future Work
- Incorporate additional data sources and features for improved accuracy
- Explore advanced models like Random Forest or XGBoost
- Develop an interactive dashboard for real-time prediction and visualization
- Investigate long COVID effects and long-term patient outcomes

## Acknowledgments
Thanks to the open-source community and dataset providers for enabling this analysis.

## Contact
Katlego Masela
maselakatlego513@gmail.com
