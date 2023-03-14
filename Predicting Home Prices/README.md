### Introduction:
The Home Price Prediction in Bangalore project aims to build a machine learning model that predicts the price of a house in Bangalore, India based on various features such as location, square footage, number of bedrooms, and other amenities. The dataset used in this project contains information about houses in Bangalore, including their location, size, and price.

### Data Preprocessing:
The total square footage can be a range, and in such cases, the average of the minimum and maximum values in the range will be used. Additionally, unusual values such as those measured in square meters will be dropped.
A new feature called price per square feet will be added to the dataset.
Locations with fewer than 10 data points will be tagged as "other" to reduce the number of categories. This will be achieved using dimensionality reduction techniques.

### Outlier Removal:
Outliers will be removed using two methods:

#### Business Logic: 
Using the expert knowledge of a real estate business manager, the minimum square footage per bedroom will be set to 300. Any property with less than 300 square feet per bedroom will be removed as an outlier.
#### Standard Deviation and Mean: 
Using the standard deviation and mean values of the dataset, any properties that fall beyond three standard deviations from the mean will be removed as outliers.

### Feature Engineering:
One hot encoding will be used to convert categorical variables such as location into numerical data. This will create fewer dummy columns.

### Model Building:
After preprocessing and feature engineering, a linear regression model will be built to predict the price of a house in Bangalore. The dataset will be split into training and testing sets, and the model will be trained on the training set. Cross-validation will be used to evaluate the model's performance.

### Model Tuning:
GridSearchCV will be used to find the best model based on the hyperparameters of the model. The following models will be considered:

Linear Regression
Lasso
Decision Tree Regression
The best model will be selected based on its performance.

### Testing:
Finally, the model will be tested on new data to evaluate its accuracy. The model's predictions will be compared to actual prices to determine the model's accuracy.

#### For the code, documentation and additional information, please refer to the [Home_price_prediction.ipynb](https://github.com/nhBasavaraj/ML-DL-Projects_nhBasavaraj/blob/main/Predicting%20Home%20Prices/HomePricePredictBangal_%20Project.ipynb)

NOTE: 📌  For any queries or mistakes was done from my end, that need to modify Please do reach out me in [LinkedIn](https://www.linkedin.com/in/basavaraj-n-hirebidari-94982b1a9)
