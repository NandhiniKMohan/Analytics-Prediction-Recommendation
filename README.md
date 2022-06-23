# Data-Science-Analytics
## Price Prediction & Location Recommendation - Airbnb dataset

### Python, ANOVA, Regression, Hypothesis Testing

Predicts the price of Airbnb property, and finds the best location to gain maximum profit - Airbnb

Business Problem and Background:
To select profitable and popular sites for setting up Airbnb hotels and houses in the world’s largest city, New York.

The tourism industry is one of the most prominent industries that reflects economic development. With the recovery from the pandemic and with people adjusting their lives to suit the new normal, there is a question of how these industries will revert to the period of glory again.

Airbnb:
Airbnb is an American rental company that runs an online marketplace for homestays and lodging.
The platform is accessible to the public as a website and mobile application.
While Airbnb as a company does not own any of the listed properties, it earns commissions from each booking that takes place using the platform.
Airbnb helps hosts and guests to find each other.

Data:
The main data that we will be using will be from the Kaggle database, we plan to use this data which has 38277 observations and 18 variables. 
The dependent variable is price, which is a quantitative variable. In the predictor set, there are 10 qualitative variables and 8 quantitative variables, related to neighborhood, location, reviews, availability, and so on.

## METHODOLOGY:
Steps:
  Data Collection
  Data Cleaning
  Exploratory Data Analysis
  Model Selection
  Prediction
  Hypothesis Testing

Tools:
  Numpy & Pandas - Data Cleaning
  Sklearn - Modeling
  SciPy - Hypthesis Testing
  Matplotlib, Seaborn - Data Visualization

Data Split:
  Training set: 80%
  Validation set: 10%
  Test set: 10%

Models Used:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Decision Tree
  - Random Forest
  - Extra Tree
  - Gradient Boosting

Prediction Model Performance:
![image](https://user-images.githubusercontent.com/106895118/175215749-190f8b6b-e074-4701-bdf0-624643b32b0d.png)

Prediction Result:
Final Model - Gradient Boosting
Test RSME - 396.905

Hypotheses:
1. There is an association between Neighbourhood & Accommodation Type
2. Average Price differs with respect to Neighbourhood and type of accommodation
3. Average Availability differs with respect to Neighbourhood and type of accommodation
4. Average Price in Manhattan is greater than that of other Neighbourhoods

Hypothesis Testing:
1. Neighbourhood & Room Type: P_value = 1.0 (Null Hypothesis - Possible)
2. Avg Price - Neighbourhood:  5.606e-118
3. Avg Price in Manhattan > Neighbourhoods: 1.94369e-113 
4. Avg Availability - Neighbourhood : 1.222947e -136
5. Avg Availability - Room type : P_value = 0.0

Best Investment:
Based on three criteria 
  - Weighted Annual Income
  - Booking rate
  - Occupancy rate

![image](https://user-images.githubusercontent.com/106895118/175217061-239d11f7-8984-4e80-8b35-be759f5a49b6.png)

Final Location Recommendation:
![image](https://user-images.githubusercontent.com/106895118/175217199-c0a4f615-91ce-4158-aad6-12c684507bfd.png)

Ideally, the best location in terms of price for almost every type of room is Manhattan, the most popular type is Hotel Rooms. Hence for real estate investors, we would recommend investing in Hotel Rooms in the neighborhoods of Manhattan, Brooklyn, or Queens depending on the amount of money they are willing to invest and their vision.



## Sample Visualizations:
Correlation between each variable:
![image](https://user-images.githubusercontent.com/106895118/174951503-fc834838-abb5-44cd-bd77-8092c5368b08.png)

Neighbourhood Bar Plot:
![image](https://user-images.githubusercontent.com/106895118/174951546-d287dcbe-f187-43ff-a407-bd9954859c00.png)

Neighbourhood Scatter Plot:
![image](https://user-images.githubusercontent.com/106895118/174951584-5fe7a408-9fcc-4125-a840-6e73e6f4f1f7.png)

Room type Bar Plot:
![image](https://user-images.githubusercontent.com/106895118/174951620-77e0ae0f-e9a6-4a7c-95aa-e22048c0b710.png)

Room type Scatter Plot:
![image](https://user-images.githubusercontent.com/106895118/174951657-4d964a0e-e161-4e2b-a8d6-6082491aa768.png)





