# Project Name: Titanic - Machine Learning from Disaster

In this notebook, we perform an Exploratory Data Analysis (EDA) on the Titanic dataset to gain insights into the factors that contributed to passenger survival during the tragic sinking of the Titanic on April 15, 1912. The goal of this analysis is to explore the dataset, clean it, visualize relationships between key features, and generate insights that will help predict the likelihood of survival based on passenger characteristics.

# 1.Problem Definition:

How we can understand the relationships between various passenger features in the dataset (e.g., age, socio-economic class, gender, etc.) and their survival chances during the incident. This EDA aims to reveal correlations within the dataset.

# 2.Data

The dataset used in this project is sourced from Kaggle's "Titanic - Machine Learning from Disaster" competition. The dataset includes the following files:
* train.csv: The training dataset, containing passenger characteristics along with the ground truth (whether they survived or not).
* test.csv: The testing dataset, where the goal is to use the trained model to predict survival outcomes.
* gender_submission.csv: A sample submission file that shows the expected format of the predictions to be uploaded as the final result.

# 3. Approach

In this EDA we will:

* Examine the data for missing values.
* Analyze the relationships between features.
* Visualize the data using plots like heatmaps, bar charts, histograms etc.
* Perform Feature Engineering to create new variables from existing data.
* Assess correlations to identify which features are most strongly related to survival. 

# 4. Features

The dataset contains the following features:
* PassengerId: Unique ID of each passenger
* Survived: Did the passenger survive? (0 for no, 1 for yes)
* Sex: If the person is Male or Female
* Age: The age of the person
* Pclass: Ticket class of the passenger (1 = 1st, 2 = 2nd, 3 = 3rd)
* Sibsp: The number of siblings / spouses onboard
* Parch: The number of parents / children onboard
* Ticket: Ticket Number
* Fare: The price of the ticket
* Cabin: The cabin number of the passenger
* Embarked: Port of Embarkation	(C = Cherbourg, Q = Queenstown, S = Southampton)
