# CarDekho-Used-Car-Price-Prediction

objective

objective of is project is to create a data science solution for predicting used car prices accurately by analyzing a diverse dataset including car model, no. of owners, age, mileage, fuel type, kilometers driven, features and location. 
The aim is to build a machine learning model that offers users to find current valuations for used cars.

Approach:

Utilize a library such as Pandas to import data from multiple Excel files.

Examine Dataset Structure:

Explore the structure of each dataset component Understand the columns, data types, and relationships between datasets.

Data Quality Check:

Handeling missing values, outliers, and inconsistencies in the data and found out inside in data

Data Preprocessing:
Handle Missing Values:

Decide whether to impute or remove missing values based on the nature of the data.

Feature Engineering:

Extract relevant information from features like age, mileage, and others to create new meaningful features.

Transform data to make it more suitable for modeling.

Encode Categorical Variables:

Used label encoding to handle categorical variables.

Scaling:

Scale numerical features to ensure that they are on a comparable scale.Common techniques include Min-Max scaling

Exploratory Data Analysis (EDA):

Generate visualizations to understand the distribution of the target variable (used car prices) and relationships between features
![download (15)](https://github.com/drajasekar/CarDekho-Used-Car-Price-Prediction/assets/44079369/727b4e22-3a5b-48f6-b8c2-48b96f443bc8)

Model Building:

Select regression models suitable for predicting continuous values. Common choices include Linear Regression, Random Forest Regression, Support Vector Regression and  XGBoost Regression.

Model Evaluation:

Linear Regression:
MAE: 0.030964008152290702
MSE: 0.0026627955757648272
RMSE: 0.051602282660409775
R-squared: 0.7617478273346049


Random Forest:
MAE: 0.01351936973047045
MSE: 0.0008856902741257477
RMSE: 0.029760548955382993
R-squared: 0.9207533488339754

Support Vector Regression:
MAE: 0.03926238057083554
MSE: 0.002433038722843656
RMSE: 0.04932584234297125
R-squared: 0.782305195647608

XGBoost:
MAE: 0.012162860314577532
MSE: 0.0007503376522057828
RMSE: 0.027392291839234313
R-squared: 0.9328639503919366

Result XGBoost has performed well with accuracy of 93%

