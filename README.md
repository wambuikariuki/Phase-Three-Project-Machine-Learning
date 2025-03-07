# Phase-Three-Project-Machine-Learning
A machine learning project predicting H1N1 vaccine hesitancy using the NHFS dataset (2009)
# Predicting H1N1 Vaccine Hesitancy: A Machine Learning Approach

## Overview
This project analyzes vaccine hesitancy using data from the **National Flu Survey (NHFS 2009)** to predict which individuals were unlikely to receive the H1N1 vaccine. Understanding the reasons behind vaccine hesitancy is essential for shaping **effective public health strategies**, especially in addressing future pandemics like COVID-19.

## Objective
The goal of this project is to:
- **Predict individuals' likelihood** of getting the H1N1 vaccine.
- **Identify key factors** influencing vaccine hesitancy.
- **Provide insights** to public health officials for improving vaccination campaigns.

##  Business Problem
Despite strong medical evidence supporting vaccines, **vaccine hesitancy has increased**, leading to declining immunization rates and a higher risk of disease outbreaks. By identifying individuals who are hesitant, **targeted interventions** can be implemented to encourage vaccine uptake.

##  Dataset
The dataset used for this project comes from the **National Flu Survey (NHFS 2009)** and consists of **26,000 respondents**, of whom **79% did not receive the vaccine**. Key factors influencing vaccine hesitancy include:
- **Doctor recommendations**
- **Health insurance status**
- **Perceived vaccine effectiveness**
- **Risk perception**

## Methodology
To build a predictive model, the following steps were performed:

1. **Data Preprocessing**:
   - Handled missing values using **Iterative Imputer**.
   - Transformed categorical variables using **One-Hot Encoding** and **Count Encoding**.
   - Addressed class imbalance to ensure fair predictions.

2. **Model Selection & Training**:
   - Tested **six machine learning models**:
     - **Gradient Boosting Classifier (Best Performer)**
     - Decision Tree Classifier
     - Logistic Regression
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - XGBoost Classifier

3. **Evaluation Metrics**:
   - **Accuracy**: Measures overall correctness.
   - **Precision**: Ensures correct identification of hesitant individuals.
   - **Recall**: Captures vaccine-hesitant individuals who might otherwise be overlooked.
   - **F1-Score**: Balances precision and recall for better classification.

## Findings
After evaluating all models, the **Gradient Boosting Classifier** achieved the highest accuracy and precision, making it the most effective model for predicting vaccine hesitancy. Key findings include:
- **Doctor recommendations** play the most significant role in vaccination decisions.
- **Health insurance coverage** is strongly linked to vaccine uptake.
- **Public perception of vaccine effectiveness** significantly impacts hesitancy.
- **Higher perceived risk of H1N1** increases the likelihood of getting vaccinated.

## Recommendations
Based on the analysis, the following recommendations can help **increase vaccination rates**:
**Enhance doctor recommendations** – Doctors play a crucial role in influencing vaccination decisions.  
**Improve vaccine accessibility** – Address barriers for those without health insurance.  
**Prioritize public education** – Awareness of vaccine effectiveness and H1N1 risk strongly impacts vaccination rates.  

## Next Steps
- Apply **advanced feature engineering** to improve model performance.
- Use more **recent flu survey data** to analyze trends over time.
- Extend the analysis to **seasonal flu vaccination** predictions.

