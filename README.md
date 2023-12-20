# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project is to retrieve information using APIs, joining the retrieved data together and performing exploratory data analysis on it, as well as building a regression model to demonstrate possible relationships between the number of bikes in a particular location within Dublin, Ireland and the review counts for nearby pubs.  

## Process
 -[x] Step 1: Connecting to CityBikes API to retrieve information.
 
 -[x] Step 2: Connecting to Foursquare and Yelp APIs to gather information on pubs within 1000m for each station retrieved. 
 
 -[x] Step 3: Merging the information from parts 1 and 2, performing EDA on the merged information, and creating a SQLite database to store the data.
 
 -[x] Step 4: Build a regression model to see if there is any correlation between the number of available bikes and the amount of pub reviews, then interpret the result of the regression model. 

## Results
Looking into the correlation of Free bikes and Review Count the following can be observed. The R-squared indicates that 19.6% of the variance in Review Count is explained by Free Bikes. The Coefficient is 17.8121 and the low p-value associated with it indicates a possibility that this is statistically significant. This coefficient suggests that each additional unit in Free Bikes is associated with an increase of approximately 17.81 units in Review Count. In summary, the regression model suggests a statistically significant relationship between the number of free bikes and the review count in Dublin, however, there are potential areas for further investigation and this model does not take into account the date the review was posted. 

## Challenges 
**Data Quality:**
 Ensuring data quality and handling missing or inconsistent data from the use of multiple APIs leads to less data to work with. 

**Data Types:**
Unable to identify more numerical data categories that could have been beneficial to the regression model.

**API Limits:**
 The limit of API calls leads to a more conservative approach when collecting data for this project. 

## Future Goals
**Explore More Categories from Yelp and Foursquare APIs:**
Extend and enhance the analysis by exploring information from a broader range of categories such as museums, late-night eats, and tourist shops.

**Model Evaluation:**
Attempting alternative regression models or categorical models to evaluate their correlation and performance. 

**In General:**
Enhance the diversity of the dataset to provide a broader context for the regression model and to offer more insight into the factors associated with bike stations within Dublin, Ireland. 
