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
College_Basketball_Data_Cleaning.ipynb — Data preprocessing and cleaning
Win_Prob_XGBoost.ipynb — XGBoost model training and evaluation
First_Logistic_Regression.ipynb — Baseline logistic regression model

---

## 👩‍💻 Author
**Saumya Bajaj** in collaboration with members of DSGT's GT Athletics Subteam 7 
saumyabajaj1123@gmail.com  
[LinkedIn](https://linkedin.com/in/saumyabajaj)
