Titanic Dataset Analysis: Data Cleaning and Exploratory Data Analysis (EDA)

Project Overview :
This project is part of my Data Science internship at Prodigy InfoTech. The objective is to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The goal is to clean the data, analyze trends, and identify patterns associated with survival rates.

Datasets Used :
The dataset is Titanic dataset, which can be found in various repositories, including Kaggle and within Python's seaborn library.

Project Structure :
Data Cleaning: Handle missing values, correct data types, and remove unnecessary columns.
Exploratory Data Analysis (EDA): Analyze key features and their relationships with survival rates.
Data Visualization: Visualize patterns and insights using graphs.


1. Data Cleaning
Handling Missing Values:
Filled missing values in the 'Age' column with the median age.
Filled missing values in the 'Embarked' column with the mode.
Dropped the 'Cabin' column due to a high percentage of missing values.

Data Type Conversion:
Converted categorical features like 'Sex' and 'Embarked' into numerical values for analysis.

2. Exploratory Data Analysis (EDA)
Univariate Analysis:
Visualized the distribution of survival status, age, and other key features.

Bivariate Analysis:
Analyzed survival rates based on sex and passenger class.
Examined the relationship between age and fare with respect to survival.

Correlation Analysis:
Generated a heatmap to visualize correlations between different features.


Data Visualization:
Used bar plots, scatter plots, and heatmaps to illustrate key insights from the data.


Install Required Libraries:
pip install pandas numpy matplotlib seaborn

Run the EDA Script:
python EDA.py

Results and Conclusion:
The project successfully demonstrated the importance of data cleaning and EDA in understanding and deriving meaningful insights from the Titanic dataset. The findings highlight key patterns in survival rates that could inform further predictive modeling efforts.



