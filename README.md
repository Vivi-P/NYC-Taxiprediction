# NYC-Taxiprediction
Developed a model that identifies and predicts  with specific variables the estimated time a taxi in NYC takes to reach the entered location. We observed and analyzed that vendor 2 has more customers, the Mean distance is approximately 3.5 km, Standard Deviation of 4.3, which lead us to believe most trips are limited to the range of 1-10 km, the majority of the taxi trips are for 1 passenger, most of the taxi trips are usually at 6 and 7 pm or during evening hours. The weekday with most pick up times are Thrusdays and Fridays  Most of the trips are between 400 seconds to 1075 seconds, we have some trips with durations as low as 1 second, which points towards trips with 0 km distance.  Overall, most of the taxi trips occur within 1 hour with some trips duration of 5471. Our Random Forest model score with a coefficient of determination (R-squared) on the test data of 0.9998, indicating the variation in the model explains over 99% of the variation.