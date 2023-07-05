# NYCity_Trip-Pred-Modeling
Dataset: https://www.kaggle.com/competitions/nyc-taxi-trip-duration

About the data:
The dataset used for this analysis is derived from the 2016 NYC Yellow Cab trip record data,
which was made accessible through Big Query on the Google Cloud Platform.
The original source of the data is the NYC Taxi and Limousine Commission (TLC).
It includes various fields such as the time and location of taxi pickups, along with drop-off locations and trip durations.
The dataset comprises approximately 1.4 million trips that occurred during the first half of 2016.

Objective:
Predict NYC Yellow Cab duration for each trip ride

Mostly it was experimenting process to find optimum model of lightGBM (I was curious is it fast?) by combining hyperparameter using halvegridsearchcv.
I did the searching log too to see the process behind it.
