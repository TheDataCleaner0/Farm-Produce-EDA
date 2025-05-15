# Farm-Produce-EDA


## Project Overview
Agricultural data often contains inconsistencies, missing values, and outliers that can mislead analysis. In this project, we:
* Cleaned and preprocessed the dataset
* Identified and removed outliers
* Explored relationships between yield, price, production, and geography
* Generated visualizations to support key findings
* Drew conclusions that help understand profitability and regional crop trends

## Dataset
Source: /kaggle/input/farm-produce-data-80-years
Key Columns:
* GEO                                     
* Type of crop                            
* Average farm price (dollars per tonne)  
* Average yield (kilograms per hectare)   
* Production (metric tonnes)              
* Seeded area (acres)                     
* Seeded area (hectares)                  
* Total farm value (dollars)

## Data Cleaning
* Stripped whitespace from column headers and string entries
* Replaced empty strings with NaN and removed rows with missing GEO, Type of crop, or price
* Detected outliers using boxplots
* Normalized inconsistencies in categorical variables

## Exploratory Data Analysis (EDA)
* Yearly treands/patterns
* Yield vs. Price (Log-Scale)
* Regional Crop Specialization
* Crop Profitability by Region

## Tools Used - python (numpy, pandas, seaborn, matplotlib)

## Conclusion
This project demonstrates how proper data cleaning and EDA can uncover meaningful patterns in agriculture data. It offers actionable insights into crop profitability, regional advantages, and market trends.

