# Machine Learning Project(Lecture 1083)

# nbviewer Link : https://nbviewer.org/github/Blackiew57/ML_project/blob/main/ml_project.ipynb

## Overview
This project analyzes the RMS Titanic passenger data to predict survival outcomes. Developed as part of a Machine Learning course at SahmYook University, it showcases various data analysis techniques and machine learning models.

## Data

The dataset used is the famous Titanic passenger list, available on Kaggle. To use this dataset:

1. Visit [Kaggle's Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data) competition page.
2. Download the `train.csv` and `test.csv` files.
3. Place these files in the same directory as the Jupyter Notebook.

The dataset contains information such as:
- Passenger class
- Sex
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket number
- Fare
- Cabin
- Port of embarkation

## Methodology

### Exploratory Data Analysis (EDA)
- Utilized matplotlib and Seaborn for data visualization
- Analyzed feature correlations with survival rates
- Handled missing data and performed feature engineering

### Machine Learning Models
We implemented and compared several models:
- Logistic Regression
- Random Forest Classifier
- K-Fold Cross-Validation

## Results

My analysis revealed several key factors influencing survival rates on the Titanic:

1. Gender: Women had a significantly higher survival rate than men. This was likely due to the "women and children first" policy during evacuation.
2. Class: First-class passengers were more likely to survive than those in second or third class. This trend was consistent across all embarkation points.
3. Age: Children had a higher chance of survival compared to adults. The most common age group was passengers in their 20s and 30s.
4. Embarkation Point: Most passengers boarded at Southampton (S), followed by Cherbourg (C), and then Queenstown (Q). 
5. Fare: There was a positive correlation between fare price and survival rate. First-class passengers paid significantly higher fares and had higher survival rates.


---

**Note**: This project is for educational purposes only and was completed as part of a university course at SahmYook University.
