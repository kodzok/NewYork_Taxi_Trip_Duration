# NewYork_Taxi_Trip_Duration

***This repository contains the code for my exploration of the "New York Taxi Trip Duration Prediction" dataset from Kaggle.***

#### Dataset
The database was taken from the [New York City Taxi Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration/data) competition at Kaggle.
> In this competition, Kaggle is challenging you to build a model that predicts the total ride duration of taxi trips in New York City. Your primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

The base chosen was the training base (`train.csv`) containing 1458644 trip records.

The base contains the following attributes:

* id - a unique identifier for each trip
vendor_id - a code indicating the provider associated with the trip record
* pickup_datetime - date and time when the meter was engaged
dropoff_datetime - date and time when the meter was disengaged
* passenger_count - the number of passengers in the vehicle (driver entered value)
* pickup_longitude - the longitude where the meter was engaged
* pickup_latitude - the latitude where the meter was engaged
* dropoff_longitude - the longitude where the meter was disengaged
* dropoff_latitude - the latitude where the meter was disengaged
* store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
* trip_duration - duration of the trip in seconds
