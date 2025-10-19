# Win Probability Model for College Basketball

This project focuses on developing a **win probability model** that predicts a college basketball team's likelihood of winning at any point during a game. The model is based on historical game data and leverages statistical and machine learning techniques.

---

## Project Goal
The goal was to estimate **real-time win probability** using play-by-play and game-level statistics.

---

## Methodology

### 1. Data Collection & Cleaning
- Collected detailed play-by-play and team statistics data from college basketball seasons.
- Cleaned raw data by handling missing values, correcting team names, and converting timestamps.

### 2. Modeling Approach
Multiple models were tested to estimate the probability of a team winning given the game state:
- **Logistic Regression** — provided interpretability and a strong baseline.
- **XGBoost Regressor** — used for non-linear interactions and higher accuracy.

### 3. Insights 
- Including possession and time-based features greatly improved predictive stability.

---

## Repository Structure
Games Data - Contains game data files by season
College Basketball Data Cleaning V2.ipynb - Data preprocessing and cleaning
College Basketball Data CleaningV1.ipynb - Initial data preprocessing and cleaning
First_Logistic_Regression.ipynb - Initial logistic regression model
README.md - Description file for the repository
Win_Prob_Xgboost.ipynb - XGBoost model training and evaluation
WinningPrediction.ipynb - Baseline logistic regression model for predicting whether the home team wins a given game
winprobmodelSS.ipynb - Final summary and scaling study for the win probability model

---

## 👩‍💻 Author
**Saumya Bajaj** in collaboration with members of DSGT's GT Athletics Subteam 7 
saumyabajaj1123@gmail.com  
[LinkedIn](https://linkedin.com/in/saumyabajaj)
