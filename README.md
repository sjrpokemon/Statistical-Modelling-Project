# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
The goal of this project is to assess and model the relationship between Point of Interest (POI) attributes and the perceived bike availability at stations. We aim to classify stations into two categories: "Enough bikes" and "Not enough bikes" based on survey responses. The model will be utilized to predict the number of bikes needed at a station or for planning new stations.

## Process
- Step 1: Data Collection
    - Gathered data on bike stations, POI attributes, and conducted a survey on perceived bike availability.
- Step 2: Data Preparation
    - Merged survey data with existing data, handling missing values and ensuring         compatibility for modeling. 
    - Selected relevant POI attributes as features.
- Step 3: Model Training
    - Utilized logistic regression to model the relationship between POI attributes and perceived bike availability.
    - Split data into training and testing sets for model evaluation.
- Step 4: Model Evaluation
    - Assessed the model's performance using accuracy, precision, recall, and F1-score on the testing set.

## Results
The logistic regression model demonstrated a satisfactory performance in predicting perceived bike availability at stations. The chosen POI attributes played a significant role in the classification process. Factors unique to New York City's urban landscape and bike usage patterns contributed to the model's ability to discern availability perceptions effectively.

## Challenges 
- The process of setting up API calls presented a notable challenge during the project. Understanding the documentation, obtaining necessary API keys, and configuring the requests required careful attention. 
- Integrating data from Foursquare and Yelp, which were initially stored as separate CSV files, posed a significant challenge. 
- Defining Foursquare and Yelp as Separate CSV Files

## Future Goals
Explore additional stations such as busses, ferries to overview transportation data in New York.
Expand the model to predict the number of bikes needed at stations more precisely.
We can also look at the trip duration data on how much rides by hour and day people typically use the city bike and put more bikes at stations which customers use more.