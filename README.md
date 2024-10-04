# 311 Service Requests from 2010 to Present: Data Mining

## Overview

This project analyzes the NYC 311 service requests dataset to identify trends in complaints over time and develop a predictive model for complaint types. It employs machine learning techniques, particularly using a Random Forest classifier, to assess and predict complaint occurrences based on various features.

## Dataset

The dataset used in this project contains service requests from NYC's 311 system from 2010 to the present. It includes information about complaint types, timestamps, and boroughs, which are crucial for understanding service demand and complaint patterns.

## Usage
Load the Dataset:

You can load the dataset using Pandas in your Jupyter notebooks or scripts:

## Loading the Dataset

To load the NYC 311 service requests dataset into a Pandas DataFrame, use the following code:

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('data/311_Service_Requests_from_2010_to_Present_20240823.tsv', delimiter='\t')

```
## Data Analysis:

Use the data_analysis.ipynb notebook to explore the dataset, visualize complaint trends, and answer specific questions regarding complaints over time, by borough, and by complaint type.

## Model Training:

The model_training.py script contains code for training a Random Forest classifier.

Modify the script as needed to fit your specific modeling requirements.

## Predictive Modeling:

The predictive_model.ipynb notebook allows you to refine your model and evaluate its performance using cross-validation and various metrics.


## Key Components
  -Data Exploration: Inspect and visualize complaint trends over time.
  
  -Complaint Type Prediction: Implement a Random Forest classifier to predict complaint types based on available features.
  
  -Visualization: Generate plots to display findings regarding complaint distributions by borough, ZIP code, and more.


## Results
After running the analysis and training the model, you will have insights into complaint trends and an accuracy score of the predictive model. Check the notebooks for detailed results and visualizations.




## Data Information

The dataset used in this project can be found at the following links:

- **[311 Service Requests from 2010 to Present](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9)**: This link directs you to the NYC Open Data portal for the complete dataset.

- **[Data Dictionary](https://data.cityofnewyork.us/api/views/erm2-nwe9/files/7bdd2c6b-ad79-438e-9ae6-2ce75b471063?download=true&filename=311_ServiceRequest_2010-Present_DataDictionary_Updated_2023.xlsx)**: This data dictionary provides detailed information about the fields included in the dataset, which is essential for understanding the data structure and contents.


## Acknowledgments
-NYC Open Data for providing the 311 service request dataset.

-Libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn for their powerful data manipulation and modeling capabilitie
