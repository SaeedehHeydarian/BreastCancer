# Breast Cancer Dataset Analysis
## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Contributing](#contributing)
## Introduction
Welcome to the Breast Cancer Dataset Analysis repository! This project aims to analyze and explore a breast cancer dataset using Jupyter Notebook. The dataset contains information about various attributes related to breast cancer, and the Jupyter Notebook codes perform data preprocessing, visualization, and predictive modeling.
## Dataset
The breast cancer dataset used in this project is publicly available from the Kaggle. The dataset involved female patients with infiltrating duct and lobular carcinoma breast cancer (SEER primary cites recode NOS histology codes 8522/3) diagnosed in 2006-2010. You can find more details about the dataset [here](https://www.kaggle.com/datasets/reihanenamdari/breast-cancer).
## Feature 
 - Race:  ['White' 'Black' 'Other']
- Marital Status:  ['Married' 'Divorced' 'Single ' 'Widowed' 'Separated']
- T Stage:  ['T1' 'T2' 'T3' 'T4']
- N Stage:  ['N1' 'N2' 'N3']
- 6th Stage:  ['IIA' 'IIIA' 'IIIC' 'IIB' 'IIIB']
- differentiate:  ['Poorly differentiated' 'Moderately differentiated' 'Well differentiated' 'Undifferentiated']
- Grade:  ['3' '2' '1' ' anaplastic; Grade IV']
- A Stage:  ['Regional' 'Distant']
- Estrogen Status:  ['Positive' 'Negative']
- Progesterone Status:  ['Positive' 'Negative']
- Status:  ['Alive' 'Dead']
 N Satge = N refers to whether cancer has spread to nearby lymph nodes. N1, N2, and N3 indicate that cancer has spread to nearby lymph nodes. A Stage: refer to M refers to whether the cancer is metastatic, which means it has spread to distant parts of the body.
## Installation
To run the Jupyter Notebook codes, you need to have Python 3 installed on your system along with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- ## Analysis Steps

1. Data Loading and Preprocessing:
   - Load the breast cancer dataset using pandas.
   - Check for missing values and handle if necessary.
   - Explore the distribution of the target variable.

2. Exploratory Data Analysis (EDA):
   - Visualize the distribution of individual features.
   - Explore correlations between features.
   - Compare the distributions of features for malignant and benign cases.

3. Feature Selection:
   - Use statistical tests or feature importance techniques to select relevant features.

4. Model Building:
   - Split the data into training and testing sets.
   - Train machine learning models for classification (e.g., xgboost, Random Forest).

5. Model Evaluation:
   - Evaluate the model's performance using appropriate metrics (accuracy, precision, recall, etc.).
   - Fine-tune the model if necessary.

6. Conclusion:
   - Summarize the findings from the analysis.
   - Discuss potential implications and limitations of the study.

# Contributing
If you would like to contribute to this project, feel free to create a pull request.






