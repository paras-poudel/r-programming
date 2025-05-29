Airline Customer Satisfaction Analysis in R
--------------------------------------------

Overview
---------

This project explores airline customer satisfaction using real-world review data. It includes data cleaning, visual analysis, and logistic regression modeling in R, suitable for intermediate R users and master's students in data analytics or business.
Airline Customer Satisfaction Analysis in R
Overview
This project explores airline customer satisfaction using real-world review data. It includes data cleaning, visual analysis, and logistic regression modeling in R, suitable for intermediate R users and master's students in data analytics or business.

Libraries Used
- tidyverse: For data wrangling and visualization
- caret: For building and evaluating models
- ggcorrplot: For correlation heatmaps
- reshape2: For reshaping data

Dataset
• File: Airline Reviews.csv
• Target Variable: Satisfaction (satisfied vs neutral/dissatisfied)
• Features: Seat comfort, inflight entertainment, online booking, delays, etc.

Analysis Steps
1. Load and inspect data
2. Handle missing values using mean imputation
3. Group by satisfaction and summarize average ratings and demographics
4. Visualize satisfaction trends, delays, and service features
5. Build logistic regression model to predict satisfaction
   
Key Visual Insights
- Seat comfort and entertainment strongly influence satisfaction
- Arrival delays reduce satisfaction significantly
- Business travelers and higher-class passengers are generally more satisfied
  
Predictive Modeling
Logistic regression was used to identify the most influential factors on satisfaction. Key predictors include comfort, booking experience, and delay times.

