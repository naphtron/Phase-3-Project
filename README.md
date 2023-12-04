# TELCO CUSTOMER CHURN PREDICTION
![Logo](https://atrium.ai/wp-content/uploads/2021/07/What-stops-customer-churn-Having-a-centralized-data-hub-does-and-heres-why.jpeg)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
## Overview
The Telecommunications (Telco) industry, a cornerstone of global connectivity, offers diverse services from traditional voice communication to cutting-edge data transmission. Telco companies, relying on robust network infrastructures, are pivotal in connecting individuals, businesses, and devices worldwide. In this dynamic landscape, they navigate technological advancements and competition, adapting to regulatory shifts and consumer demands. Telecom companies strive to deliver reliable and innovative communication services, shaping the way people and organizations connect, communicate, and access information in the modern world.

## Installation and Setup
### Code and Resources Used
 - Editor: Google Colab (https://colab.research.google.com/)
-  Python version: Python 3.9
-  Code: customer_churn.ipynb
### Python Packages Used
- Data Manipulation: Pandas, Numpy
- Data Visualization: Matplotlib, Seaborn
- Modeling: Sklearn

## Repository Structure

├─ data

     ├─ Telco-Customer-Churn.csv
   
├─ README.md

├─ customer_churn.ipynb

├─ presentation.pdf

## Data
### Source Data
- Telco Customer Churn Dataset - (https://www.kaggle.com/datasets/blastchar/telco-customer-churn/download?datasetVersionNumber=1)
### Features
 - Categorical features: `Customer ID`, `Gender`, `Senior Citizen` (binary), `Partner` (binary), `Dependents` (binary), `Phone Service` (binary), `Multiple Lines` (categorical), `Internet Service` (categorical), `Online Security` (categorical), `Online Backup` (categorical), `Device Protection` (categorical), `Tech Support` (categorical), `Streaming TV` (categorical), `Streaming Movies` (categorical), `Contract` (categorical), `Paperless Billing` (binary), `Payment Method` (categorical), `Churn` (binary, target variable).
- Numerical features: `Monthly Charges`, `Total Charges`, `Tenure` (in months).
- 
### Exploratory Data Analysis
During the EDA phase, the primary focus was to analyze the relationship between customer churn and various features. Here are key findings:
#### Distribution of Churn(feature)
![Logo](https://github.com/naphtron/Phase-3-Project/blob/master/imgs/Churn%20Distribution.png)

#### Churn Rate by Gender
![Logo](https://github.com/naphtron/Phase-3-Project/blob/master/imgs/Churn%20Rate(Gender).PNG)

#### Churn Rate by Tenure(Grouped)

-  **"Tenure"** refers to the duration or length of time a customer has been using the services provided by the company
  
![Logo](https://github.com/naphtron/Phase-3-Project/blob/master/imgs/Churn(tenure).png)

### Modeling
#### Method / Algorithms.
- The project employs an iterative approach in the construction of models.

- The methodology initiates with the establishment of a baseline model, incorporating logistic regression and a decision tree, subsequently advancing to a more sophisticated model, namely the Random Forest algorithm.

- In addressing the nuances of this specific problem, the evaluation metric selected is recall. The performance assessment of models is conducted based on this chosen metric.

- Subsequently, the identified model is subjected to a tuning process with the aim of enhancing its overall performance.

#### Results
##### General Results
![Logo](https://github.com/naphtron/Phase-3-Project/blob/master/imgs/Model_table.PNG)

##### Results sorted by Recall
![Logo](https://github.com/naphtron/Phase-3-Project/blob/master/imgs/recall%20table.PNG)

