# The Bet Advisory - Machine Learning Project 2024

This project simulates a bet advisory service, providing predictions on upcoming football matches across major European leagues. Users can set a desired risk profile, ranging from the safest (1) to the riskiest (3), and receive weekly predictions on games. We then analyze the results and potential monetary returns.

## Data Collection

We collected historical match data from the Bundesliga, Premier League, La Liga, Serie A, and Ligue 1, spanning from the 2014/2015 to 2021/2022 seasons. Each season’s data is labeled for tracking historical performance.

## Feature Engineering

Key features include disciplinary scores, team form, matchup history, and rolling averages of various team stats. Data is split into training and testing sets, with the test set comprising the second half of the 2021/2022 season.

## Modeling

### Risk Profiles
- **Risk Profile 1:** Predictions with a probability of 75% or higher (safest).
- **Risk Profile 2:** Predictions with a probability of 65% or higher (moderate).
- **Risk Profile 3:** Predictions with a probability of 55% or higher (riskiest).

### Algorithms
- **Random Forest Classifier**
- **XGBoost Classifier**

Models are trained on historical data and make predictions week by week.

## Evaluation

The accuracy of predictions and potential returns are evaluated for each risk profile. The distribution of odds for correct and incorrect predictions is analyzed to assess returns.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/the-bet-advisory.git
   cd the-bet-advisory
