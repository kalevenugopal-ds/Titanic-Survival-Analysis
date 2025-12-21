# Titanic Exploratory Data Analysis (EDA)
## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the key factors that influenced passenger survival during the disaster.
The analysis focuses on demographic and socio-economic features such as **gender, age, and passenger class**.
This project demonstrates an end-to-end data science workflow including **data cleaning, exploratory data analysis, and machine learning**.
## Objectives
- Understand the structure of the Titanic dataset
- Identify missing values and data distributions
- Analyze survival patterns based on different features
- Extract meaningful insights using visualizations
## Dataset Information
- **Dataset Name**: Titanic Dataset
- **Source**: Kaggle
- **Rows**: 891
- **Columns**: 12
- **Target Variable**: `Survived`
## Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
## Exploratory Data Analysis Steps
1. Data loading and inspection
   
2. Understanding data types and structure
3. Missing value analysis
4. Univariate analysis
5. Bivariate analysis (Survival vs Gender, Class, Age) 
6. Key insights and conclusions
## Key Insights
- Female passengers had a **much higher survival rate** than males
- **First-class passengers** survived more compared to lower classes
- Male passengers in **third class had the lowest survival rate**
- Age had a noticeable impact on survival probability
## Conclusion
- The analysis shows that survival on the Titanic was **not random**.
- Factors such as **gender, passenger class, and age** played a major role in determining survival outcomes.
- This EDA provides a strong foundation for building **predictive machine learning models**.
## Future Work
- Feature engineering
- Machine learning models (Logistic Regression, Decision Tree)
- Survival prediction
# Machine Learning Model – Logistic Regression
## 🔹 Model Objective
The goal of this model is to predict whether a passenger survived the Titanic disaster based on demographic and travel-related features.
## 🔹 Features Used
- Passenger Class (Pclass)
- Sex (Sex)
- Age (Age)
- Fare (Fare)
- Port of Embarkation (Embarked)
- Categorical variables were encoded using:
  - Label Encoding for Sex
  - One-Hot Encoding for Embarked
## 🔹 Model Training
- **Model**: Logistic Regression
- **Train–Test Split**: 80% training, 20% testing
- **Random State**: 42
## 🔹 Model Performance
- **Accuracy**: ~79.9%
- **True Positives**: 55
- **True Negatives**: 88
- The model performed well for a baseline classifier and demonstrated the impact of **gender and passenger class** on survival prediction.
## 🔹 Evaluation Summary
Although the dataset is imbalanced, Logistic Regression achieved strong performance without complex tuning. Further improvements could be made using additional models and evaluation metrics.
## Author
**Venugopal Kale**
Aspiring Data Scientist
## Project File
- `Titanic_EDA.ipynb`
