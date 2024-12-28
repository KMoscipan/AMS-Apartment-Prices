
# Amsterdam Apartment Price Analysis

## Overview  
This project explores the factors that influence apartment prices in Amsterdam for September 2024, using data scraped from Funda. It highlights key elements like apartment size, neighborhood, energy efficiency, and room count as the main price drivers. An Ordinary Least Squares (OLS) regression model is used to understand these relationships and provide useful insights.

## Objective  
The goal of this project is to identify the main factors that drive apartment prices in Amsterdam and create a predictive model using OLS regression.

## Key Insights  
- **Main Price Drivers:** Size and neighborhood pricing are the most important factors influencing apartment prices.  
- **Other Factors:** Energy efficiency and the number of rooms also impact prices, but to a lesser degree.  
- **Data Cleaning:** Outliers were removed to focus on typical market conditions, which helps make the model more relevant for the average buyer.  
- **Model Performance:** The OLS model explains around 72% of the variance in apartment prices (R-squared = 0.72).

## Future Enhancements  
- **Expand Data:** Including more data from other months could make the model more robust and capture trends over time.  
- **Improve the Model:** Trying regularization techniques (like Ridge or Lasso regression) and experimenting with other models (e.g., Random Forests) could improve predictions.

## Conclusion  
This analysis provides a clear picture of the factors that influence apartment prices in Amsterdam. It shows how data-driven methods can offer valuable insights into the real estate market. For a deeper dive into the analysis, check out the [Jupyter notebook](https://github.com/KMoscipan/AMS-Apartment-Prices/blob/main/Amsterdam_Apartment_Prices.ipynb).
