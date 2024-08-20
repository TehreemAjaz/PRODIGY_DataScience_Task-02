# PRODIGY_DataScience_Task-02

Description of Data Cleaning and Exploratory Data Analysis (EDA)
Data Cleaning
Handling Missing Values:

Age: Missing values in the Age column were filled using the median age. The median was chosen because it is less affected by outliers compared to the mean, providing a robust measure of central tendency for this numerical feature.
Embarked: Missing values in the Embarked column, which represents the port of embarkation, were filled using the mode. The mode was used because it identifies the most frequently occurring category, making it a suitable choice for categorical data.
Handling Test Data:

Rows with missing values in the Fare column of the test dataset were removed, as this feature is critical for analysis and modeling.
Converting Categorical Data to Numerical:

Sex: The Sex column was converted from categorical labels ('male' and 'female') to numerical values (0 and 1). This transformation is necessary for many machine learning algorithms that require numerical input.
Embarked: The Embarked column was encoded into numerical values representing different ports of embarkation (0 for 'C', 1 for 'Q', 2 for 'S').
Removing Non-Numeric Columns:

Columns that were not useful for numerical analysis or modeling, such as Name, Ticket, and Cabin, were dropped from both the training and test datasets.
Exploratory Data Analysis (EDA)
Survival Distribution:

The distribution of survival outcomes was visualized to understand the proportion of passengers who survived versus those who did not.
Age Distribution:

The distribution of ages among passengers was examined to understand the age range and its distribution, including any potential patterns or anomalies.
Survival by Gender:

The survival rates were compared between different genders to explore any disparities in survival chances.
Survival by Passenger Class:

The survival rates were analyzed across different passenger classes (Pclass) to see if there were differences in survival probabilities based on class.
Age vs. Fare:

A scatter plot was created to investigate the relationship between a passenger's age and the fare they paid, with survival status indicated by color. This helps to understand if there are any trends or patterns linking these two variables to survival.
Correlation Matrix:

A heatmap of the correlation matrix was generated to examine the relationships between numerical features. This matrix helps to identify strong correlations and potential multicollinearity among features.
Pairplot of Features:

A pairplot was used to visualize pairwise relationships between selected features, such as Age, Fare, Pclass, and Survived. This visualization aids in understanding the interactions and correlations between different features.
