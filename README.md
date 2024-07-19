# IPL-Machine-Learning-Score-Predictor

IPL Score Predictor
This Streamlit web application enables users to predict the total runs scored in an IPL match using current match data such as runs and wickets.

Algorithms Used
This project utilizes various machine learning algorithms for prediction:

Linear Regression
K-Nearest Neighbors Regressor
XGBoost Regressor
Random Forest Regressor
Support Vector Regressor (SVR)
Decision Tree Regressor
Hyperparameter Optimization
Optuna has been used for hyperparameter optimization to improve the performance of the models.

Dataset
The dataset contains over-by-over details of IPL matches and runs from 2008 to 2020.

Dataset Columns
mid: Match ID
date: Date when the match was played
venue: Venue of the match
bat_team: Batting team
bowl_team: Bowling team
batsman: Batsman
bowler: Bowler
runs: Runs scored
wickets: Wickets taken
overs: Overs
run_last_5: Runs scored in the last 5 overs
wicket_last_5: Wickets taken in the last 5 overs
striker: Batsman on strike
non-striker: Batsman at the non-striker's end
total: Total score (target variable)
Dataset Used
The dataset used for this project is ipl_data.csv.

Streamlit App
This app provides an interactive interface to input match data and predict the total runs.
