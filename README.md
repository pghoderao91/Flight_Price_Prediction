# Flight_Price_Prediction


## INTRODUCTION:
Flight ticket prices are notoriously unpredictable, fluctuating daily due to factors like demand, seasonality, and route popularity. This variability often leaves travelers uncertain about the best time to book tickets, while airlines face challenges in optimizing revenue. By applying machine learning, we aim to develop a model that predicts future flight prices, helping travelers plan cost-effective journeys and assisting airlines in setting competitive prices. This project involves analyzing historical flight price data and building a predictive model to offer accurate price forecasts, benefiting both customers and airlines.

## BUISNESS CASE:
The business case is to predict flight prices to help travelers book cost-effectively and enable airlines to optimize pricing strategies.

## Task : Regression Problem

## DATA PREPROCESSING AND FEATURE ENGINNERING:

1.	MISSING VALUE:
•	In this data no missing value is present.

2.	CATEGORICAL DATA:
•	There were 4 categorical column we have perfomed Manual and Frequency encoding on it.

3.	OUTLIER HANDLING:
• In this data the outlier were handle through IQR method	

4.	FEATURE SCALING:
 •   No scaling was done has it has distrubted the quality of data

## FEATURE SELECTION:

1.	DROP UNIQUE AND CONSTANT COLUMN:
•	In this data only one unique column is present

2.	CHECK THE CORRELATION:
•	In this data no highly correlated feature is present

3.	CHECK DUPLICATES:
•	There is no duplicates present in data

## MODEL CREATION AND SELECTION:

###  OBSERVATION:

*	The Gradient Boosting Regressor with Hyper-Parameter Tuning delivers the best results, with an R² score of 0.8236, an Adjusted R² of 0.8226, and a MAE of 1,432. This indicates high accuracy and good generalization with minimal overfitting.
*	The Decision Tree Regressor performs decently, achieving an R² score of 0.7866 and MAE of 1,499, while the Random Forest Regressor has the lowest performance with an R² score of 0.6889 and a MAE of 1,432.
