House Price Prediction – Project Summary
Objective
The objective of this project was to build a machine learning model that can predict house prices based on various property features such as area, number of bedrooms, bathrooms, parking facilities, and other amenities. The project also aimed to identify the factors that have the greatest influence on house prices.
Dataset Description
The dataset used for this project consisted of 545 house records and 13 features. The target variable was price, while the remaining columns were used as input features. The dataset contained both numerical and categorical data. After exploring the dataset, it was found that there were no missing values and no duplicate records, indicating that the data was already clean and well-structured.
Data Preprocessing
The categorical features such as mainroad, guestroom, basement, airconditioning, and furnishingstatus were converted into numerical form using one-hot encoding so that machine learning algorithms could process them. The dataset was then divided into training data (80%) and testing data (20%).
Model Development and Evaluation
Two regression models were developed and compared:
1.	Linear Regression
o	MAE: 970,043
o	RMSE: 1,324,507
o	R² Score: 0.653
2.	Random Forest Regressor
o	MAE: 1,021,546
o	RMSE: 1,400,566
o	R² Score: 0.612
Based on the evaluation metrics, the Linear Regression model performed slightly better than the Random Forest model for this dataset, achieving a higher R² score and lower prediction errors.
Key Findings
Feature importance analysis showed that the following factors had the greatest impact on house prices:
•	Area of the house
•	Number of bathrooms
•	Availability of air conditioning
•	Parking facilities
•	Number of stories
•	Number of bedrooms
Among all the features, area was by far the most influential factor, contributing nearly half of the overall importance in predicting house prices.
Conclusion
This project demonstrated that machine learning can effectively be used to estimate house prices using property characteristics. An interesting observation was that amenities such as air conditioning, parking, and furnishing status significantly affected house prices even when houses had similar sizes. For real estate businesses, using predictive models can help determine fair property prices, support investment decisions, and provide better recommendations to buyers and sellers.

