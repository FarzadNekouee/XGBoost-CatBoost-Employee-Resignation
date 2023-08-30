## 🚀 Employee Resignation Prediction | XGBoost vs CatBoost Regressors
![Employee Resignation Prediction](image.jpg)

## 🌐 Overview
This repository contains a project focused on predicting employee resignations. The dataset includes a variety of features related to employees, such as satisfaction level, last evaluation, and number of projects. The primary objective is to develop a predictive model that accurately determines whether an employee will leave the company. This prediction is essential for organizations as employee turnover can significantly impact productivity, operational planning, and expenses associated with recruiting, hiring, and training new employees.

## 🌟 Problem
In this project, we aim to build a predictive model to determine whether an employee will leave the company, which is crucial for organizations as employee turnover affects productivity, operational planning, and recruiting expenses. The dataset contains various features related to employees, such as satisfaction level, last evaluation, and number of projects, which adds to the complexity of the model. The challenge lies in the data preprocessing steps, which include encoding categorical features, handling missing values, and tuning the hyperparameters of the models. Additionally, we are going to train XGBoost and CatBoost regressors, evaluate their performance using the right metrics, and interpret the models by analyzing the most important features in the context of employee resignations.

## 🎯 Objectives
The objectives of the project are as follows:

* **Dataset Overview**: Investigate the dataset's basic information, including summary statistics for numerical and categorical variables.
* **Conduct Extensive Exploratory Data Analysis (EDA)**:
  - Analyze the distribution of numerical features against the target variable.
  - Analyze the distribution of categorical features against the target variable.
* **Data Preprocessing**:
  - Check for missing values.
  - Encode categorical features.
* **Model Building**:
  - Define XGBoost and CatBoost Regressors.
  - Tune the hyperparameters for both models to achieve the best performance.
  - Evaluate the performance of both models using regression metrics like MAE, MSE, RMSE, and R2 Score.
* **Conclusion**: Summarize the findings, compare the performance of the models.

## 📚 Dataset Description
The dataset comprises various metrics related to employees. The features of the dataset are described in the table below:

| __Variable__ | __Description__ |
|     :---      |       :---      |      
| __satisfaction_level__ | The level of satisfaction of the employee |
| __last_evaluation__ | The score of the last evaluation of the employee |
| __number_project__ | The number of projects the employee has worked on |
| __average_montly_hours__ | The average monthly hours worked by the employee |
| __time_spend_company__ | The number of years the employee has spent at the company |                     
| __Work_accident__ | Whether the employee had a work accident (1 = yes, 0 = no) |
| __left__ | Whether the employee has left the company (1 = yes, 0 = no) |  
| __promotion_last_5years__ | Whether the employee had a promotion in the last 5 years (1 = yes, 0 = no) |                      
| __sales__ | The department the employee works in |
| __salary__ | The salary level of the employee (low, medium, high) |

## 📁 File Descriptions
- 📓 **`Employee_Resignation_Prediction.ipynb`**: Jupyter notebook containing data exploration, visualization, modeling, and evaluation code.
- 📁 **`HR.csv`**: CSV file containing the employee dataset.
- 📘 **`README.md`**: This file, providing an overview of the project.

## 🚀 Instructions for Local Execution
1. **Clone this Repository**: Begin by cloning this repository to your local setup.
2. **Open the Notebook**: Access the `Employee_Resignation_Prediction.ipynb` in Jupyter.
3. **Install Dependencies**: Ensure all necessary Python libraries are installed for seamless execution.
4. **Execution**: Run all cells in the notebook to witness the results and insights.

## 🔗 Additional Resources
- 🌐 **Kaggle Notebook**: If you're keen on a Kaggle environment, delve into the notebook [here](https://www.kaggle.com/farzadnekouei/code).
- 🤝 **Connect on LinkedIn**: Have queries or looking for collaborations? Feel free to connect on [LinkedIn](https://linkedin.com/in/farzad-nekouei-7535aa53/).

