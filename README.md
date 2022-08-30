# Bangalore_House_Prediction

<b><i>The house price predictor using Kaggle dataset and Machine Learning Algorithms</i></b>

## About
<p>
In this project, we used a machine learning model to predict the prices of houses in the city 
of Bangalore. This model is based on multiple linear regression, based on features like area,
number of bedrooms and bathrooms, location etc. We also used lasso regression and 
decision tree, compared the accuracy of the three models using grid search method (it was 
found that multiple regression had the highest accuracy among the three models). An 
accuracy rangingfrom 82-85 per cent was obtained.
</p>
<p>
  In this project, we have taken into consideration a dataset containing data
from over 10000 houses in Bangalore from different locations within the city.
</p>

## Installation and Running
* Clone the Repository
* Run `Bangalore House Price Prediction.ipynb` file in `./models` folder
* Run `server.py` present in `./server` folder
* Run `app.html` present in `./client` folder
* All Done !

<p>
<b>NOTE : </b> This Site can be deployed on the Local Machines
</p>

## Related Work
<p>
Famous real estate companies such as Magicbricks and Zillow.com use such regression-based
models for different cities. Zillow.com has a house selection feature which is based on
multiple linear regression. This feature of Zillow is known as Zestimate.
</p>

## Data Cleaning Methodology
* Removal of null values
* Replacing ranges with mean (e.g.: 1120-1200 would become 1160)
* Removing outliers
* Categorizing data
* Removing features with high correlation or redundance.

## Results
Libraries used: Pandas, NumPy, Matplotlib, SKLearn
Models used: <strong>Multiple linear regression, K-Means, Lasso Regression, Decision tree.</strong>
Metrics used: GridSearchCV
Accuracy: MLR = 82.02%; Lasso = 67.9%; Decision tree = 71.03%
