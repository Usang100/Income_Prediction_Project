#  Income Prediction Using Census Data (Capstone Project)

##  Overview

This project is part of my CareerEx Data Science program, where I built a **machine learning model** that predicts whether an individual earns **less than $50K** annually, based on their demographic and work-related attributes.

Using a real-world census dataset of over 48,000 records, the model identifies patterns from features like age, education, occupation, marital status, and hours worked per week.


## Objective

The primary goal was to:
- Build a model that can generalize on **unseen data**
- Focus on accurately predicting the **>50K income class**
- Handle class imbalance effectively
- Evaluate models using **Evaluation Metrics** 

## Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Key Steps

- **Data Cleaning & Exploration** (EDA)
- **Preprocessing** using Pipelines & ColumnTransformer
- **Model Training** using Logistic Regression, Decision Tree, Random Forest, SVM, and XGBoost
- **Hyperparameter Tuning** with GridSearchCV
- **Model Evaluation** using Confusion Matrix, F1-score, ROC-AUC
- **Final Model Selection** based on performance metrics

## Final Results

| Model              | Accuracy | F1-score (>50K) | ROC-AUC |
|-------------------|----------|-----------------|---------|
| Logistic Regression | 85.3%   | 0.67            | 0.91    |
| Decision Tree       | 86.1%   | 0.67            | 0.90    |
| Random Forest       | 86.5%   | 0.68            | 0.92    |
| XGBoost (Best)      | **87.6%** | **0.72**       | **0.93**|


##  Real-world Use Cases

This kind of income prediction model can be helpful for:
- **Government agencies**: Social planning, policy-making
- **NGOs**: Targeting financial aid to low-income groups
- **Businesses**: Income-based segmentation and personalized marketing
- **Researchers**: Studying income patterns and inequality

> _"From data to decision — this project reflects my journey of learning, building, and delivering value with machine learning."_ 
