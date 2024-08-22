# CODTECH-TASK1
*Name* : PRIYANSHI VARSHNEY

*Company*: CODETECH IT SOLUTION

*INTERN* *ID* : CT04DS6919

*Domain* : DATA ANALYST

*Duration* : AUGUST 2024 TO SEPTEMBER 2024

*Mentor*  : MUZAMMIL AHMED

Project Overview: Titanic Dataset Exploratory Data Analysis (EDA)
Objective:
The primary objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset. EDA helps us understand the data’s characteristics, distributions, correlations, and outliers, providing insights into the factors influencing passenger survival rates on the Titanic. The analysis involves cleaning, visualizing, and interpreting data to draw meaningful conclusions.

Key Activities:

Data Loading and Understanding:

Loaded the Titanic dataset using the Pandas library.
Inspected the data structure, including data types, missing values, and overall shape.

Univariate Analysis:

Examined the distribution of numerical features like age and fare using histograms.
Analyzed categorical features such as passenger class (Pclass) and port of embarkation (Embarked) using bar plots.

Bivariate Analysis:

Investigated relationships between features, focusing on how they influence the target variable (Survival).
Created bar plots to observe survival rates across different passenger classes.
Computed and visualized a correlation matrix using a heatmap to understand the relationships between numerical variables.


Handling Missing Values and Outliers:

Addressed missing values by filling in the median age and the most common port of embarkation.
Identified and handled outliers in the fare distribution by capping extreme values.


Visualization:

Utilized Seaborn and Matplotlib to create histograms, bar plots, heatmaps, and pair plots for data visualization.
Visualized pairwise relationships among selected features to gain further insights.


Technology Used:

Python Programming Language: The core language used for data analysis and visualization.

Pandas: For data manipulation and analysis, including handling missing values and computing descriptive statistics.

Numpy: For numerical operations and efficient handling of data arrays.

Matplotlib and Seaborn: For data visualization, enabling the creation of histograms, bar plots, heatmaps, and more.


Key Insights:

Survival Rates and Passenger Class:

Passengers in higher classes (1st class) had significantly higher survival rates compared to those in lower classes.


Age and Survival:

The median age of passengers who survived was slightly lower than those who did not. The analysis suggested that younger passengers had a slightly better chance of survival.


Correlation Between Features:

The fare paid by passengers had a positive correlation with survival, indicating that wealthier passengers had a higher likelihood of surviving.
Passenger class negatively correlated with survival, reinforcing the observation that lower-class passengers had lower survival rates.


Data Cleaning:

Missing values in the Age and Embarked columns were successfully handled, ensuring that the dataset was complete for analysis.
Outliers in the fare column were capped to prevent skewing the results.


Conclusion:

The Exploratory Data Analysis of the Titanic dataset provided valuable insights into the factors influencing passenger survival. The analysis revealed significant correlations between passenger class, fare, age, and survival rates. By cleaning the data, handling missing values, and addressing outliers, the dataset was made more reliable for further analysis or modeling tasks. The visualizations and statistical summaries help understand the underlying patterns in the data, guiding future predictive modeling efforts.
