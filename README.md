# primeo

🧩 Problem Statement

This notebook focuses on analyzing and predicting property listing prices using the dataset listing_for_modeling.csv. The dataset includes features such as bedrooms, bathrooms, accommodates, latitude, longitude, and review_scores_rating. The goal is to uncover key factors driving price variations and build a model that can predict listing prices accurately and reliably.

🧩 Objectives

Perform Exploratory Data Analysis (EDA) to identify data patterns, skewness, and outliers influencing the listing price distribution.

Apply feature selection techniques (VIF, SelectKBest, RFE) to retain only the most relevant predictors for price modeling.

Build  Linear Regression model to forecast property prices effectively.

Evaluate model performance using R², RMSE, MAE, and MAPE to ensure reliable and interpretable results for price estimation.

🧩 summary

What patterns, distributions, and outliers exist in the dataset that affect listing prices?
 EDA revealed that price, accommodates, and bedrooms were right-skewed with a few extremely high-priced outliers. The majority of listings had mid-range prices, and normalization was necessary to reduce skewness.

Which features contribute most significantly to predicting the price of a listing?
Feature analysis found that accommodates, bedrooms, bathrooms, and review_scores_rating are the top influencers of price. Multicollinearity between spatial and size-related features was minimized using VIF and SelectKBest.

How well do the models perform in terms of R², RMSE, MAE, and MAPE — and what does this imply about prediction reliability?
The LR model achieved R² = 0.81, RMSE ≈ 4.6%, MAE = 0.18, and MAPE ≈ 3.6%, reflecting predictive accuracy and strong generalization capability.
