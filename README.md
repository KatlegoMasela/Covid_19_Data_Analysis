COVID-19 Data Analysis and Predictive Modeling

Overview

This project involves analyzing COVID-19 patient data to identify key risk factors, visualize trends over time, and develop predictive models for patient mortality. The goal is to support healthcare decision-making by providing actionable insights into patient outcomes.

Objectives

- Clean and preprocess COVID-19 patient data

- Engineer relevant features (age groups, comorbidities, severity levels)

- Perform exploratory data analysis (EDA) to uncover patterns and trends

- Visualize death trends over time

- Identify patient clusters based on health conditions

- Build and evaluate a logistic regression model to predict mortality risk

Dataset

The dataset used in this project contains anonymized patient records, including demographic information, medical conditions, treatment indicators, and outcomes.
Source: Local COVID-19 dataset (Covid Data.csv.zip)

Technologies & Libraries

- Python 3.x

- Pandas, NumPy for data manipulation

- Matplotlib, Seaborn for visualization

- Scikit-learn for clustering and modeling

- Jupyter Notebook for interactive analysis

Methodology

1. Data Collection & Exploration

- Loaded and inspected data to understand structure and content

- Handled missing values appropriately

- Created new features such as age groups and severity indicators

2. Data Visualization

- Analyzed trends in death rates over time using rolling averages

- Visualized distributions of key variables (age, comorbidities, severity)

3. Clustering Analysis

- Applied KMeans clustering to identify patient segments based on features like age and comorbidity count

4. Predictive Modeling

- Defined core features (AGE, COMORBIDITY_COUNT, SEVERE_CASE, HAS_COMORBIDITY)

- Split data into training and testing sets

- Trained a logistic regression model to predict patient mortality (DIED)

- Evaluated model performance using classification metrics

Results & Insights

- Key risk factors for mortality include advanced age, higher number of comorbidities, and being classified as a severe case.

- Distinct patient clusters suggest targeted intervention strategies could improve outcomes.

- The logistic regression model provides a baseline for mortality risk prediction, aiding healthcare providers in resource allocation.

Future Work

- Incorporate additional data sources and features for improved accuracy

- Explore more advanced modeling techniques (Random Forest, XGBoost)

- Develop a user-friendly dashboard for real-time prediction and visualization

- Analyze long-term effects and long COVID implications

Acknowledgments

Thanks to the team and open-source community for providing datasets and tools that made this analysis possible.

Contact

Katlego Masela
maselakatlego513@gmail.com
