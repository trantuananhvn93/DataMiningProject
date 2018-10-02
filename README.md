# DataMiningProject
This mini project aims to build a XGBoost model to predict the total ride duration of taxi trips in New York city.

## Data
Data could be downloaded from [Kaggle](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)
**Description**

- train.csv - the training set (contains 1458644 trip records)
- test.csv - the testing set (contains 625134 trip records)

**Features**

`id` - a unique identifier for each trip
`vendor_id` - a code indicating the provider associated with the trip record
`pickup_datetime` - date and time when the meter was engaged
`dropoff_datetime` - date and time when the meter was disengaged
`passenger_count` - the number of passengers in the vehicle (driver entered value)
`pickup_longitude` - the longitude where the meter was engaged
`pickup_latitude` - the latitude where the meter was engaged
`dropoff_longitude` - the longitude where the meter was disengaged
`dropoff_latitude` - the latitude where the meter was disengaged
`store_and_fwd_flag` - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
`trip_duration` - duration of the trip in seconds

## Report
[report link](https://github.com/trantuananhvn93/DataMiningProject/blob/master/report%20taxi.pdf)
