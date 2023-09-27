# Air-Flight

This datasets are acquired from Kaggle, and I attempt to analyse flight delay and ticket prices and install machine learning models to forecast the delays and ticket prices.
## Flight Delay Analysis and Prediction

Datset : https://www.kaggle.com/datasets/sherrytp/airline-delay-analysis (2022) 

It's a big data project

The project is about predicting flight delays using machine learning. It involves analyzing a dataset of airline flights and their various attributes, such as departure and arrival times, airline carrier, and weather conditions. The dataset has missing data that needs to be addressed, and some of the attributes need to be transformed to make them suitable for modeling.

The project then uses exploratory data analysis techniques to gain insights into the data, such as visualizing the distribution of delays and exploring relationships between different attributes.

Next, the project focuses on classification modeling, using three different classifiers: logistic regression, decision tree, and random forest. The dataset is prepared for modeling by encoding categorical features and removing multicollinearity effects (i.e., removing highly correlated attributes).

To improve the performance of the models, undersampling and oversampling techniques are used to balance the dataset. Finally, feature selection is performed to identify the most important attributes for predicting flight delays.

The project concludes with a summary of the modeling results and recommendations for which model to use for predicting flight delays. The code and results are shared on Github for others to use and build upon.


## Flight Ticket Price Prediction

Dataset : https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh

I performed a detailed analysis on various flight-related factors to predict flight ticket prices. The factors included flight duration, departure and arrival times, date of journey, total stops, additional information, airline, source and destination, and route.

After conducting exploratory data analysis and feature engineering, I built and evaluated two machine learning models: linear regression and random forest. The linear regression model helped me understand the relationships between the predictor variables and the target variable (ticket price), while the random forest model was able to capture non-linear relationships and interactions between the variables.

Using these models, I was able to accurately predict flight ticket prices based on the input variables. This analysis can be useful for airlines, travel agencies, and customers to plan and book their flights in a more informed and cost-effective way.
