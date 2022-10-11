
# Uber and Lyft Cab prices analysis
### Dataset Used
* https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices?select=weather.csv

Dataset contains 'simulated' rides for Uber and Lyft in NYC in 2016 from a 2-week period of time.

### Methods Used
* Data Analysis
* Data Visualization
* Machine Learning

### Technologies
* Python
* Pandas, jupyter
* scikit-learn
* tensorflow

## Project Description
This is my first Data Science project. Project was made in order to obtain information about Taxi rates. Provided data was from 'simulated' rides so it was only possible to explore one feature which was price. After some explorations, it was hard to say that price is correlated with anything but distance feature. I suppose that one of key factors determing price is a number of available drivers but unfortunately that information is not provided by Uber and Lyft. After preliminary analysis I moved on to prediction section. Firstly I tried to applay Linear Regression model to predict the price of a ride, however the results were not the best ones. It may be caused by a of lack of linear correlations beetwen features. Nevertheless this model was able to predict price with some uncertainty. The second model that I built was a Neural Network which was used to perform the same action. Interestingly Neural Net gives worst results than Linear Regression. Source code, plots, models and conclusion are available in project file.

