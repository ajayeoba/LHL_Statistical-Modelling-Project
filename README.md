# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The Goal of get statistical data using API requests. And use the result to build a statistical model to get insite on the relationship between the number of available bikes in a bike station and the average distance between the bike station and restaurants

## Process
Step 1: Understand the API data using the API documentation and sample results
Step 2: Collected data from CityBikes (https://citybik.es/) by calling its api endpoint and specifying location. The result contained details about the bike station including the longitiude, latitude and number of Bikes in that chosen location 
Step 3: Collected Restaurant data from Foursquare API and Yelp API by passing the latitude and longitude rerieved from the CityBikes Bike stations
Step 4: Joined data retrieved from Foursquare API and Yelp API 
step 5: Explored the data using data Visualisation 
step 6: Created a database from the merged data using sqlite
step 7: created a model to show the relationship between the number of available bikes and the average distance to restaurants in that location 



## Results
Observing Vancouver, foursquare API seem to have the higher quality of data. I observe it has more attribute. For example, foursquare API provide muliple category for each restaurant. so i can observe the different at a glance which restaurant has the most variants of food. 
initial observations on the scatter plot shows an increase in  yelp average distance with increase in foursquare average distance. Which shows that the data are similar
Also observed there is a linear relationship between price and rating. 

Also it doesnt look like there are any correlation between change in distance of restaurant and how it affects the number of free bikes

R-Squared
R-squared which is the measurement of how much of the targed variable is explained by changes in our model predictor. R-squared value of explains how the dependent variable explains the bike availability

Adj. R-Squared
adjusted R-squared is very close to the R-squared. This could be because we are only using one feature in our model


Null Hypothesis (H0): The number of available bikes at a specific location is not significantly affected by the average distance of restaurants from that bikestation

Alternative Hypothesis (H1): The number of available bikes at a specific location is significantly affected by the average distance of restaurants from thatbikestation


Pvalue: the value of p-values is greater than 0.05. This implies that there is insufficient evidence to reject the null hypothesis. This implies that the average distance of restaurants from bikestation might not significantly influence the number of available bikes in that bike station

## Challenges 
API request limit on the YELP API gave a challenge when i got the request failed due to Yelp API.



## Future Goals
1. With unlimited API request, I will be able to explore multiple features and point-of-interest. Explore other location and compare correlation base on city
2.  Explore other regression techniques







