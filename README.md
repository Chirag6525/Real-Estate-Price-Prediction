# Real-State-Price-Prediction
Real Estate Price Prediction is the process of estimating or forecasting the future prices of real estate properties, such as houses, apartments, or commercial buildings. The goal is to provide accurate property rates to buyers, sellers, investors, and real estate professionals to make informed decisions about real estate transactions.
## Dataset
- Transaction date: The date of the real estate transaction.
- House age: Age of the house in years.
- Distance to the nearest MRT station: Distance to the nearest Mass Rapid Transit station in meters.
- Number of convenience stores: Number of convenience stores in the vicinity.
- Latitude: Latitude of the property location.
- Longitude: Longitude of the property location.
- House price of unit area: House price of unit area.
## Correlation
- **House Age:** This shows a very weak negative correlation with house price (-0.012), implying that age is not a strong predictor of price in this dataset.
- **Distance to Nearest MRT Station:** Has a strong negative correlation with house price (-0.637). It indicates that properties closer to MRT stations tend to have higher prices, which is a significant factor in property valuation.
- **Number of Convenience Stores:** Displays a moderate positive correlation with house price (0.281). More convenience stores in the vicinity seem to positively affect property prices.
- **Latitude and Longitude:** Both show a weak correlation with house prices. Latitude has a slight positive correlation (0.081), while longitude has a slight negative correlation (-0.099).
## Linear Regression
Linear regression is a fundamental statistical technique used to model the relationship between a dependent variable (often called the response variable) and one or more independent variables (predictors).

**- R2_score**:0.54 
