### Titanic Dataset - Exploratory Data Analysis (EDA)

# 📚 Project Overview
This project performs an in-depth Exploratory Data Analysis (EDA) on the classic Titanic dataset.
The goal is to understand the underlying patterns, relationships between variables, and factors that influenced passenger survival.

The Titanic dataset is a common introductory dataset for machine learning and data analysis tasks, containing demographic and survival information of passengers aboard the Titanic.
__

# 📂 Dataset Information

The dataset includes the following key features:

- PassengerId: Unique ID for each passenger

- Survived: Survival (0 = No, 1 = Yes)

- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)

- Name: Name of the passenger

- Sex: Gender

- Age: Age in years

- SibSp: # of siblings / spouses aboard

- Parch: # of parents / children aboard

- Ticket: Ticket number

- Fare: Passenger fare

- Cabin: Cabin number

- Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

# 🛠 Steps Performed

1.Data Loading

Loaded the dataset using pandas.

2.Data Cleaning

- Handled missing values (especially in Age, Cabin, and Embarked).

- Converted categorical variables where necessary.

- Dropped irrelevant or highly missing columns (e.g., Cabin, depending on the strategy).

3.Univariate Analysis

- Analyzed individual features such as Age, Sex, Pclass, and Fare.

- Plotted histograms, boxplots, and countplots to understand distributions.

3.Bivariate and Multivariate Analysis

- Studied relationships between features and the target (Survived).

- Compared survival rates across Sex, Pclass, Age, and Embarked.

- Used heatmaps to visualize correlations.

4.Feature Engineering

-Created new features like:

FamilySize = SibSp + Parch 

- One Hot Encoding

- Outlier Removal


# Key Insights

Women had a much higher survival rate compared to men.

First-class passengers survived at a much higher rate than lower classes.

Younger passengers (especially children) had better survival odds.

Solo travelers had lower survival chances compared to those traveling with family.

Data Visualization

Used matplotlib and seaborn libraries.

Plotted survival rates across different features.


# 📊 Technologies Used
- Python

- Pandas

- NumPy

- Matplotlib

- Seaborn

-Jupyter Notebook for interactive analysis


# ✨ Conclusion
The EDA reveals significant patterns regarding who survived the Titanic disaster, providing a strong foundation for future predictive modeling (e.g., building a classification model to predict survival).

Proper data cleaning, feature engineering, and visualization were critical steps in uncovering these insights.

