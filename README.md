
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
This is my first Data Science project.
Project was made to explore some information about Taxi rates. Whole data was from 'simulated' rides so it was only possible to explore price feature.
After some explorations, it was hard to say that price is correlated with other than distance feature. I guess one of key factors determing price is a
number of available drivers but Uber and Lyft do not share this information. 
After I did some analysis I moved on to prediction section. Firstly i tried to train Linear Regression model to predict price of ride. It was done but results are not best ones. I think it is because of lack of linear
correlations beetwen features. Nevertheless model can predict price with some uncertainty. Second model that
I built was a Neural Network which was used to the same action. Interestingly Neural Net gives worst results than Linear Regression.
Source code, plots, models and conclusion are available in project file.

