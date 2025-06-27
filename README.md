# Titanic Dataset Analysis

![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/600px-RMS_Titanic_3.jpg)

## Project Overview
This repository contains my analysis of the Titanic dataset, completed as Task 2 of my Data Science internship. The project demonstrates essential data science workflows including data cleaning, feature engineering, and exploratory data analysis (EDA).

## Key Features
- **Data Cleaning**: Handled missing values in 'Age' and 'Embarked' columns
- **Feature Engineering**:
  - Extracted passenger titles from names
  - Created family-related features (FamilySize, IsAlone)
- **Exploratory Analysis**:
  - Survival rate by gender (74% female vs 19% male)
  - Survival rate by passenger class (63% 1st class vs 24% 3rd class)

## Technologies Used
- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## Getting Started
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Open and run `Prodigy_DS_Task2.ipynb`

## Insights
![Survival by Gender](images/survival_by_gender.png)
![Survival by Class](images/survival_by_class.png)

## Future Work
- Implement machine learning models
- Hyperparameter tuning
- Model deployment

## Dataset Source
[Kaggle Titanic Competition]([https://www.kaggle.com/c/titanic](https://www.kaggle.com/c/titanic/data))
