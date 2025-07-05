Data Cleaning & EDA
Overview
Cleaned and explored the Titanic dataset to identify factors affecting survival.

Data Cleaning
Filled missing Age with median.

Dropped Cabin due to many missing values.

Filled missing Embarked with mode.

Converted categorical columns.

Created FamilySize and IsAlone features.

Sample Code
python
Copy
Edit
df['Age'] = df['Age'].fillna(df['Age'].median())
EDA Highlights
Higher survival for females and 1st class passengers.

Explored survival by age, fare, family size, and embarkation port.
