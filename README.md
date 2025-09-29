# task-5-EDA
📌 Objective

The goal of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to identify trends, patterns, and relationships that influenced survival.

🛠 Tools & Libraries
Python
Pandas
NumPy
Matplotlib
Seaborn
📂 Dataset

We used the Titanic dataset (titanic dataset.csv) from Kaggle.

Target column: Survived (0 = Did not survive, 1 = Survived).
Key features: Age, Sex, Pclass, Fare,  etc.
🔎 Steps Performed

Data Cleaning

Handled missing values:
Filled missing Age with median.
Dropped Cabin (too many missing).
Filled Embarked with mode.
Verified no null values remain.

Univariate Analysis

Survival distribution.
Gender distribution.
Age and Fare distributions.

Bivariate Analysis

Survival vs Gender.
Fare vs Survival.

Multivariate Analysis

Correlation heatmap.
Pairplot of selected features.
📊 Key Insights
Gender: Females had a much higher survival rate than males.
Class: Passengers in 1st class had significantly better survival chances compared to 3rd class.
Age: Younger children had higher survival rates compared to older passengers.
Fare: Higher fare passengers survived more often, indicating wealth played a role.
