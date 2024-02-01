Capstone Project - Brainstation Data Science Bootcamp
November 2023 - February 2024
Welcome to my Capstone Project for the Brainstation Data Science Bootcamp. This intensive project, spanning from November 2023 to February 2024, represents a culmination of my learning and hands-on experience in the field of data science.

Project Overview
Project Description
This capstone project focuses on developing a predictive analysis tool within the realm of medical data science. It targets critical health conditions such as heart failure, stroke, diabetes, and cancer, aiming to predict the likelihood of these diseases based on a combination of medical and demographic data.

Objective
The primary objective is to harness the power of data science and machine learning to provide early warnings for critical health conditions. This initiative is geared towards aiding in early diagnosis and thereby improving patient outcomes.

Key Challenges
Data Quality and Reliability: Ensuring the accuracy and reliability of the datasets utilized.
Model Accuracy and Validation: Developing models that are not only precise but also clinically valid.
Handling Imbalanced Data: Addressing the prevalent issue of imbalanced datasets in medical data science.
Ethical Considerations: Navigating data privacy and ethical concerns in healthcare analytics.

Technologies Used
Programming Languages: Python, with a focus on libraries such as Pandas, NumPy, and Scikit-learn.
Data Visualization: Employing tools like Matplotlib and Seaborn for insightful visualizations.
Machine Learning Frameworks: Exploring advanced modeling with TensorFlow or PyTorch.

Expected Outcomes
Project: A robust, reliable predictive model for disease risk assessment.
Personal Development: Enhanced skills and expertise in data science, particularly in its application to healthcare.

Why This Project?
My passion lies at the intersection of data science and healthcare. This project presents an opportunity to make a tangible impact on patient care through predictive analytics. It aligns with my aspiration to apply data science in solving real-world challenges while furthering my expertise in a vital domain.


Stroke Prediction and Analysis
Introduction
Strokes have a significant impact on global health, with an astonishing fact that 80% of strokes are preventable. This analysis delves into key indicators leading to strokes, encompassing data from various age groups, genders, habits, and health conditions. Our goal is to present intuitive visualizations that effectively communicate crucial information.


Problem Statement
The focus is to visualize and understand the relationship between lifestyle habits and the occurrence of heart strokes. We aim to predict the probability of strokes using finely tuned models, thereby contributing to preventive health strategies.


Questions and Assumptions
Our investigation revolves around several key questions and assumptions:


Impact of Age: Exploring the influence of age on stroke occurrence and its distribution across different populations.
BMI and Glucose Levels: Examining the correlation between higher BMI and glucose levels with stroke risk.
Smoking and Stroke Risk: Investigating the potential link between smoking habits and increased stroke risk.
Heart Disease and Stroke: Assessing the relationship between existing heart conditions and stroke occurrences.
Workload and Blood Pressure: Analyzing if high workload and subsequent blood pressure increases contribute to stroke risk.
Gender-Specific Risks: Evaluating whether males are more prone to strokes due to work-related stress or if the risks vary across genders.

Methodology
Data Analysis: Thorough examination of the dataset to understand feature distributions and interrelationships.
Visualizations: Employing various plots and charts to reveal patterns and insights.
Statistical Testing: Utilizing statistical methods to validate assumptions and hypotheses.
Model Building: Creating predictive models to estimate stroke risk.
Feature Importance: Identifying and focusing on key factors that significantly influence stroke risk.
Feature Selection: Selecting the most relevant features to enhance model accuracy and performance.

Conclusion
This project aims to provide a comprehensive understanding of the factors leading to strokes and their interactions. The insights gained are crucial for formulating effective preventive measures and early intervention strategies.

Balanced Category Representation: The even distribution across categories suggests a well-balanced representation. This balance is advantageous, as it minimizes the risk of bias towards any specific category in the modeling process.

Enhanced Model Generalizability: Models developed from this dataset are likely to be more generalizable due to the diverse exposure to all categories, enhancing their applicability across varied data scenarios.

Reduced Need for Imbalance Handling Techniques: The uniformity in distribution negates the necessity for specialized techniques typically used to address data imbalance, streamlining the modeling process.

Uniform Contribution to Predictive Power: Each category is likely to contribute more evenly to the model's predictive capabilities, although the actual impact would also depend on the correlation of these categories with the target variable.

Simplified Feature Engineering: Given the balanced distribution, complex feature engineering steps, such as category combination or transformation, may not be required unless specific domain knowledge or hypotheses dictate otherwise.

Applicability of Standard Evaluation Metrics: In this balanced scenario, standard evaluation metrics like accuracy might be more relevant, compared to scenarios with imbalanced data where metrics like precision, recall, and F1-score are typically more informative.

Opportunities for Further Exploration: While the distributions are uniform, further exploratory analysis, especially in relation to other features or the target variable, could reveal more nuanced relationships or interactions.


<div align="center">

# 📈 Loan Default Prediction Project: Paycast

<img align="center" src="https://github.com/rachellliao/loan-default-prediction/blob/98162956ba8f0143e2b5a6c7752c3a14b0149be9/Paycast%20Logo.png" title="Paycast" alt="Paycast" width="400" height="400"> 

</div>

## 🎯 Project Overview

This project leverages machine learning to predict loan payment statuses accurately. By doing so, it offers lending institutions enhanced risk assessment, decision-making processes, and the potential to minimize financial losses.

## 📊 Dataset

The dataset comes from **LendingClub**, a prominent peer-to-peer lending platform in the United States. Each row represents a unique loan, and each column a different loan attribute, including:
- Loan amount
- Term
- Interest rate
- Grade, sub-grade
- Employment title, employment length
- Home ownership
- Annual income

## 🚀 Project Workflow

### 🧹 [Data Cleaning](https://github.com/rachellliao/loan-default-prediction/blob/2e01b69b68ba27228ba69b5b7e328b89e5373cc0/1.%20data_cleaning.ipynb)
We started by tidying up the dataset: removing irrelevant features, handling missing data, and eliminating any features not available at loan issuance time.

### 🕵️‍♂️ [Exploratory Data Analysis (EDA)](https://github.com/rachellliao/loan-default-prediction/blob/2e01b69b68ba27228ba69b5b7e328b89e5373cc0/2.%20EDA.ipynb)
EDA helped understand feature distributions and relationships with loan status, thus informing model choice and guiding feature engineering.

### 🧠 [Feature Engineering](https://github.com/rachellliao/loan-default-prediction/blob/2e01b69b68ba27228ba69b5b7e328b89e5373cc0/3.%20feature_engineering.ipynb)
We transformed existing data through one-hot encoding, converting categorical variables into machine-learning-friendly formats.

### 📊 [Modeling](https://github.com/rachellliao/loan-default-prediction/blob/ed9ca37c0e91f0eb600b2ede8dc56de457491cf8/4.%20modeling.ipynb)
We tested and evaluated various models, including:
- Logistic Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- XGBoost

The **Random Forest model** was chosen for its superior performance.

## 📝 Findings and Conclusions
The best-performing model boasts an accuracy of ~80% and correctly identifies 93% of loans paid off, enhancing risk assessment.

Potential improvements include:
1. **Addressing Class Imbalance:** The dataset had many more loans that were paid off than defaulted. Techniques such as random oversampling could be used to address this imbalance.
2. **Incorporating More Features:** Additional features not included in the current dataset could potentially enhance the predictive power of the model.
3. **Trying Different Models:** While the Random Forest model performed best in this project, other techniques such as neural networks, or ensemble methods could potentially yield better results.
4. **Balancing Power with Interpretability:** Depending on the needs of the end user, future work could focus on models that balance predictive power with interpretability.


This project demonstrates the practical application of data science techniques in predicting loan defaults and provides valuable insights for risk assessment in lending institutions. Future work will aim to further improve the model's performance and interpretability.

