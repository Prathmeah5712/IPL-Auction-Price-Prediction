# 🏏 IPL Player Auction Price Prediction

## Problem Statement
IPL franchises spend crores on players during auctions. 
I built a regression model to predict a player's auction 
price based on their performance stats.

## What I Did
- Performed EDA on 12,000 player records
- Handled outliers using IQR capping method
- Compared 4 ML models: Linear Regression, Decision Tree,
  Random Forest, Gradient Boosting
- Built new features: Runs_per_Match, Wickets_per_Match
- Deployed app using Streamlit

## Key Finding
Interestingly, traditional performance stats (Runs, Wickets)
showed very low correlation with auction price — suggesting
that real IPL prices are driven by star value and brand 
factors, not just raw performance numbers.

## Tech Stack
Python | Pandas | Scikit-learn | Matplotlib | Seaborn | Streamlit

## How to Run
pip install -r requirements.txt
streamlit run app.py
