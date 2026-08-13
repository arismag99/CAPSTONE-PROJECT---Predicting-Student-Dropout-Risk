# CAPSTONE-PROJECT---Predicting-Student-Dropout-Risk
This project presents the complete implementation of a machine learning project entitled "Predicting Student Dropout and Academic Success Using Machine Learning Techniques." The project utilizes the publicly available Students Dropout and Academic Success dataset to develop predictive models capable of classifying students into three academic outcomes: Dropout, Enrolled, and Graduate. By analyzing demographic, socioeconomic, financial, and academic variables, the study aims to uncover the key factors influencing student success and build an accurate predictive framework that can support institutional decision-making.
The project follows the standard data science lifecycle, beginning with problem understanding and framing, followed by data collection and understanding, data preprocessing, exploratory data analysis (EDA), and feature engineering. Multiple supervised machine learning algorithms—including Logistic Regression, Decision Tree, Random Forest, Support Vector Machine (SVM), and XGBoost—were implemented and evaluated to determine the most effective predictive model. The study also incorporates feature importance analysis, model explainability, and ethical AI practices, including fairness and bias auditing, to ensure that the resulting models are not only accurate but also transparent, interpretable, and responsible.
Throughout the project, appropriate evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and the Confusion Matrix were used to compare model performance. In addition, explainable AI techniques, including SHAP and LIME, were considered to provide meaningful interpretations of model predictions and to support informed educational decision-making. Ethical considerations, fairness assessments, and bias mitigation strategies were also explored to ensure that the predictive models promote equitable treatment of students from diverse backgrounds.
# studentAcademicOutcome
# Student Academic Outcome Prediction Using Machine Learning

A machine learning project that predicts student academic outcomes using supervised multiclass classification.

## Project Overview

This project analyzes the Students Dropout and Academic Success dataset and compares different machine learning models to predict student outcomes.

The dataset contains **4,424 student records** with demographic, socioeconomic, financial, and academic variables. The target variable is `Target`:

* `Dropout` = Student discontinued the program
* `Enrolled` = Student remains enrolled
* `Graduate` = Student successfully completed the program

Dataset source:  
https://www.kaggle.com/datasets/adilshamim8/predict-students-dropout-and-academic-success

## Models Used

The following models were developed and compared:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

## Data Processing

The project includes:

* Data cleaning and inspection
* Duplicate checking
* Missing-value checking
* Outlier analysis
* Categorical encoding
* Feature scaling
* Exploratory data analysis
* Correlation analysis
* Random Forest feature importance
* Feature selection

## Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The **Random Forest** model was selected for the main explainability analysis because it provided a strong balance between predictive performance and interpretability.

## Explainability and Fairness

The project also used:

* SHAP
* LIME
* Partial Dependence Plots (PDP)
* Individual Conditional Expectation (ICE)
* Fairness and bias analysis

The explainability analysis showed that academic progression, particularly curricular units approved and semester grades, were important factors in predicting student outcomes.

## Repository Structure

- notebook/
- src/
- data/
- models/
- lime explanations/
- report/
- presentations/

## Tools and Libraries

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SHAP
* LIME
* Joblib
* SciPy
* Matplotlib
* Seaborn

## Installation

Install the required libraries using:

```bash
pip install -r requirements.txt
```

The complete list of required libraries is provided in `requirements.txt`.

## Note

This project is intended for academic and analytical purposes. The predictive model is designed as a decision-support and early-warning tool and should not replace professional judgment in student-related decisions.
