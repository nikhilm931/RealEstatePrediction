# RealEstatePrediction
This study uses realtor data about various properties across the US, filtered down to Philadelphia and New York to make classification and regression predictions of pricing based on historical data.

# Description
Real estate pricing after the pandemic was extremely volatile. As a result, it was difficult for first-time home buyers to decide when they should purchase property. We attempt to solve this problem with our project that takes data about properties sold between 2018-2020, and making predictions about pricing for properties sold in or after 2022. The goal of this project is to apply classification and regression models to the features that influence pricing to make predictions about real estate pricing in New York City and Philadelphia. The classification models sorted properties into ranges of pricing, and the regression models attempted to make predictions as accurately as possible to the true pricing. 

# Potential Use and Stakeholders
The main stakeholders are individuals who are seeking to purchase property in the next year sometime and want to understand where the market is going in the future based on past data. It could also be useful for banks that provide home loans, mortgage companies, and escrow companies. 

# Data Source
This data came from Realtor.com, and it contains data on properties sold in the United States from 2018-2022. 

# Methods Used
- Linear Regression
- Logistic Regression
- Decision Tree Regressor and Classifier
- Random Forest Regressor and Classifier
- XGBoost Regressor

# Getting Started
1. Clone this current repo
2. Raw data is kept within this folder as "realtor-data.csv"
3. Code in "Philly and New York Prediction.ipynb" can be reviewed and revised as needed. Run all code to view results.

# Issues and Limitations
This project was mainly limited by the features that we used. There are more economic factors that contribute the true pricing of real estate, and not all were considered in this study. In addition, there were time constraints for this project due to Graduate School deadlines, so future work could create more accurate predictions. 
