# NYCTaxiFarePrediction

This dataset was proposed as a [challenge at Kaggle](http://kaggle.com/c/new-york-city-taxi-fare-prediction/). It contains a `train.csv` file, consisting of around 55M entries, and a `test.csv` file having around 10k entries. The features given are: `pickup_datetime`, `pickup_longitude`, `pickup_latitude`, `dropoff_longitude`, `dropoff_latitude` and `passenger_count`. The objective of the challenge is to predict `fare_amount` based on these features.

Though I trained a model in a sample of 250,000 rows, my main concern this time was on data exploration, data cleaning and feature engineering. This got me even to a new package that I used to plot coordinates over an actual map. Pretty sweet!
