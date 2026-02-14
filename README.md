Objective

The aim of this task is to clean raw data and understand it using statistics and visualizations.
We handled missing values, converted text data to numbers, scaled features, and explored the dataset using graphs.

Tools Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Google Colab

Dataset

Dataset used: Titanic Dataset
Contains passenger information such as Age, Gender, Fare, Passenger Class, and Survival.

Steps Performed
Data Cleaning

Loaded dataset in Google Colab

Filled missing Age with median value

Filled missing Embarked with most common value

Removed Cabin column (too many missing values)

Converted Sex column → numeric (male=0, female=1)

Applied encoding on Embarked column

Standardized numerical features (Age, Fare, SibSp, Parch)

Exploratory Data Analysis (EDA)

Generated summary statistics (mean, std, min, max)

Created histograms to see data distribution

Used boxplot to detect outliers

Generated correlation matrix using heatmap

Used pairplot to understand feature relationships

Observed patterns and trends from visualizations
