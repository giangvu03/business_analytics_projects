## Data Source
The dataset was obtained from publicly available Airbnb listing data (New York City), sourced from [Inside Airbnb](https://insideairbnb.com/get-the-data/). It contains information on property characteristics, host profiles, pricing, and customer reviews. 

## Data Overview
The dataset consists of Airbnb listings in New York City, including information on pricing, location, property characteristics, and host performance.
Key features include:
  - Price
  - Room type
  - Neighborhood
  - Number of reviews
  - Review scores
  - Availability
  - Host-related attributes

## Exploratory Data Observations
Several key patterns were identified during initial data exploration:
- **Price distribution is highly skewed**, with a small number of listings priced significantly higher than the majority  
- **Location plays a critical role**, with central neighborhoods showing consistently higher prices  
- **Room type impacts pricing**, with entire homes/apartments priced higher than private/shared rooms
- Listings with **higher review scores and more reviews** tend to have higher and more stable pricing  
- Some listings show **extreme outliers**, requiring treatment to improve model performance  

## Data Cleaning Decisions
Based on the observations above, the following preprocessing steps were applied:
- Removed extreme outliers in price to reduce skewness  
- Filtered invalid or missing values (e.g., price = 0 or null entries)  
- Converted categorical variables into numerical formats for modeling  
- Selected relevant features based on business logic and correlation analysis  

