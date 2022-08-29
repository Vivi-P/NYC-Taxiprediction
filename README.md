# NYC-Taxiprediction

Developed a model that identifies and predicts  with specific variables the estimated time a taxi in NYC takes to reach the entered location. We observed and analyzed that vendor 2 has more customers, the Mean distance is approximately 3.5 km, Standard Deviation of 4.3, which lead us to believe most trips are limited to the range of 1-10 km, the majority of the taxi trips are for 1 passenger, most of the taxi trips are usually at 6 and 7 pm or during evening hours. The weekday with most pick up times are Thrusdays and Fridays  Most of the trips are between 400 seconds to 1075 seconds, we have some trips with durations as low as 1 second, which points towards trips with 0 km distance.  Overall, most of the taxi trips occur within 1 hour with some trips duration of 5471. Our Random Forest model score with a coefficient of determination (R-squared) on the test data of 0.9998, indicating the variation in the model explains over 99% of the variation.

Our team built a model that predicts the total ride duration of taxi trips in New York City. According to Kaggle, the dataset was released by NYC Taxi and Limousine Commission. Includes variables containing pickup/drop off location (longitude and latitude), time & duration by a NYC taxi company. The primary objective of this project is to predict the estimated time a taxi in NYC takes to reach the entered location given a specific location, date and time. A taxi company could use this prediction for developing policies and improving taxi distribution.

## Data used:

/kaggle/input/nyc-taxi-trip-duration/nyc_taxi_trip_duration.csv 

## Variables Description:

ID: It is a unique identifier for each trip
Vendor ID: A code indicating the provider associated with the trip record.
Pick up Date time: Date and time when taxi pick up passenger or meter was engaged.
Drop off Date time: Date and time when the taxi drop off passenger or meter was disengaged.
Passenger count: The number of passengers in the taxi.
Pick up Longitude: An angular coordinate that defines the position of a point on a surface of earth where the meter was engaged while the passenger was picked.
Pick up Latitude: The angle between the straight line in the certain point and equatorial plane where the meter was engaged while the passenger was picked.
Drop off Longitude: An angular coordinate that defines the position of a point on a surface of earth where the meter was disengaged while the passenger was drop off. 
Drop off Latitude: The angle between the straight line in the certain point and equatorial plane where the meter was disengaged while the passenger was drop off.
Store and Forward Flag: This flag indicates whether the trip log was held in vehicle memory before sending to the vendor due to the taxi not having connection to the server. Y - store and forward and N - not a store and forward trip. 
 
## Methodology:

The present study will use regression and logistic model analysis in order to select the best model to predict taxi trip duration and also Random Forest and K-Nearest Neighbors Regression. 

## Team members:

Xinshi Li
Vanessa Hidalgo
Viviana Pavon

