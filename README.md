# 1.0 Project Overview
This project provides a risk anlysis of aviation data from the NTSBA aviation databasefrom 1962 to 2023 about civil aviation accidents and selected incidents within United States and International waters.The analysis will help the company in determing the aircrafr with the lowest risk for the company to invest.
## 1.1 Business Problem
The aircraft business is an unknown business environment to the company given its history of investements 
## 1.2 Data understanding and Analyisis
The data from NTSBA database has 88889 rows and 31 columns.To undertake a conclusive analysis there is a need to drop the columns that dont relate directly to the investment in aircraft.There is also the issue of columns with so many missing values and that need also to be dropped.#df1.info()
### 1.2.0 Data Source
The analysis is using dat from Kaggle.com namely:
  AviationData.csv
  USState-Codes.csv
### 1.2.1 Description of data
The data has both numerical and categorical columns.
The data is positively skewed and the missing values will be filled with the median and for the categorical variable with the most frequent
### 1.2.3 Visualization
Making recommendations for how the business should move forward with the new aviation opportunity. 
# 1.3 Conclusion
