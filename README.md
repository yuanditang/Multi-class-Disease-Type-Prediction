# CBC Data Analysis Project

This project analyzes **diagnosed CBC (Complete Blood Count) data** to extract insights and build predictive models using various machine learning techniques. It is part of the materials used in a **workshop demonstration** that showcases data manipulation, visualization, and predictive modeling.

## Project Overview

This repository contains:
- `diagnosed_cbc_data.csv`: The dataset containing CBC test results with corresponding diagnoses.
- `f24_workshop2_demo.ipynb`: A Jupyter Notebook used for data exploration, analysis, and demonstrating machine learning workflows.

### Dataset Description

The `diagnosed_cbc_data.csv` file contains the following columns:
- **Patient ID**: Unique identifier for each patient.
- **White Blood Cell Count (WBC)**: Measurement of the number of white blood cells.
- **Hemoglobin (HGB)**: Levels of hemoglobin in the blood.
- **Platelets (PLT)**: Platelet count.
- **Diagnosis**: The medical diagnosis based on CBC values.

The dataset is used to explore the relationship between CBC measurements and various medical conditions, which are important indicators for diagnosing diseases such as anemia, infections, or blood disorders.

### Objectives

- Explore and clean the dataset.
- Conduct statistical analysis and visualization of key features.
- Build a machine learning model to predict medical diagnoses based on CBC test results.
- Use techniques such as **classification models** and **cross-validation** for model evaluation.

## Dependencies

The project requires the following dependencies:
- Python 3.x
- Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

## Usage

### Data Analysis & Visualization

The f24_workshop2_demo.ipynb notebook contains the following steps:

	1.	Data Loading: Load the `diagnosed_cbc_data.csv` dataset.
	2.	Data Cleaning: Handle missing values and perform any necessary data preprocessing.
	3.	Exploratory Data Analysis (EDA): Visualize the distribution of CBC values and analyze relationships between features.
	4.	Modeling: Train a classification model (e.g., decision trees, random forests) to predict medical diagnoses based on CBC test results.
	5.	Evaluation: Evaluate model performance using accuracy, precision, recall, and other metrics.


## Results

The analysis results and the machine learning models' performance will be displayed in the notebook. Key takeaways from the project will include:

•	Patterns identified in CBC measurements for different diagnoses.
•	The accuracy and reliability of predictive models based on CBC data.
