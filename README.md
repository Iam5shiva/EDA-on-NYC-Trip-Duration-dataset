# EDA-on-NYC-Trip-Duration-dataset
The aim of this project is just to explore the dataset and generate insights from it. 

## Dataset

* id - a unique identifier for each trip
* vendor_id - a code indicating the provider associated with the trip record
* pickup_datetime - date and time when the meter was engaged
* dropoff_datetime - date and time when the meter was disengaged
* passenger_count - the number of passengers in the vehicle (driver entered value)
* pickup_longitude - the longitude where the meter was engaged
* pickup_latitude - the latitude where the meter was engaged
* dropoff_longitude - the longitude where the meter was disengaged
* dropoff_latitude - the latitude where the meter was disengaged
* store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server (Y=store and forward; N=not a store and forward trip)
* trip_duration - (target) duration of the trip in seconds

Dataset is consisting of more than 700000 record having continuous, categorical and datetime variables.
pickup_day_name, pickup_day, pickup_month, 
## Approach
Extracted new features using datetime columns like - pickup_day_name, pickup_day, pickup_month, dropoff_day_name, dropoff_day, dropoff_month and extracted distance covered on each trip using pickup_latitude and pickup_longitude.
Performed univariate and multivariate analyses to answer below queries-
* Number of taxi vendors and trips associated with each of them?
* Number of passengers in a trip and their behaviour?
* Trips on weekdays and weekends?
* How number of trips changes according to months?
* Any network issue faced during ride?
* How much distance covered by each trips and their average?
* Effect on trip duration on the basis of day and hour?
* Relation between distance and trip duration?
