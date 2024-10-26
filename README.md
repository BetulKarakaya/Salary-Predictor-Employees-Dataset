# Salary Prediction Model

### Project Overview
<p>This project is a machine learning pipeline designed to predict employee salaries based on features like job title, department, years of experience, and other relevant factors. Utilizing powerful models like XGBoost and feature selection techniques such as Recursive Feature Elimination (RFE), the project aims to deliver accurate and insightful salary predictions.</p>

#### Table of Contents
+ Features
+ Data
+ Model Evaluation
+ Contributing
+ License
#### Features
+ **Data Preprocessing:** Handling missing values, transforming skewed data, and scaling numeric data.
+ **Exploratory Data Analysis (EDA):** Analysis and visualization of key patterns in the dataset.
+ **Feature Engineering and Selection:** Using RFE to retain the most influential features for improved model performance.
+ **Salary Prediction:** Utilizing XGBoost and optimizing hyperparameters to produce reliable salary predictions.
+ **Model Evaluation Metrics:** Using Mean Squared Error (MSE) and Mean Absolute Error (MAE) to assess model accuracy.
+ **Visualization:** Graphical analysis of feature importance, distributions, and model predictions.
#### Data
The dataset was obtained from Kaggle and is licensed under the Apache 2.0 License on the Kaggle platform. It includes features such as:

Gender
Department
Overtime Hours
Country
Years of Experience
Relationships between these factors and monthly salary information were explored using visual analysis, statistical methods, and AI-based techniques. As a result, a predictive model for salary estimation was developed.

[Employee Dataset](https://www.kaggle.com/datasets/abdallahwagih/company-employees/data)

#### Model Evaluation
The following metrics were used to assess model performance:

Mean Squared Error (MSE): 607,925.01
Mean Absolute Error (MAE): 678.04
Best Hyperparameters for XGBoost
python
```
{
    'learning_rate': 0.01,
    'max_depth': 3,
    'n_estimators': 50,
    'subsample': 0.7
}
```

#### Contributing
Contributions are welcome! If you have suggestions for improvement or new features, please submit a pull request or open an issue.

#### License
This project is licensed under the Apache License 2.0. See the LICENSE file for more details.






