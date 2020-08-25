# Predicting-El-Salvador-House-Prices
Used Scrapy to scrape and clean data from Encuentra24.com, an online marketplace in Latin America. Incorporated data from multiple online sources. 
- **Goal**: My goal was twofold: find most important predictors of house prices in El Salvador and create an model to predict house prices which could be built upon to achieve more accurate models in the future. 
- **Tools used**: Scrapy, Python
- **Year Created**: 2019
- **Results**: XGBoost achieved the best results with a 47% MAPE, compared to 89% baseline MAPE. This provided a great improvement on which the team could build upon. The high error was due to the fact that the data used was online listings data rather than property sale prices, and thus has much more noise and errors. The most important predictor found was whether the property is located in an exclusive neighborhood, which prompted the company to reevaluate investing practices to emphasize the percieved exclusivity of a property's location. 

