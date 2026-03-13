# AI-Driven Portfolio Optimisation for Irish Equities

## Project Overview

This project applies machine learning and optimisation techniques to construct an optimal portfolio of Irish equities.

The objective is to forecast market behaviour using financial features and then optimise portfolio weights to maximise risk-adjusted returns.

The project demonstrates the use of black-box optimisation and hyperparameter tuning within a financial market context.

## Dataset

Market data is collected from Yahoo Finance for companies listed on the Irish exchange (Euronext Dublin).

Example assets include:

- Ryanair
- CRH
- Kerry Group
- Bank of Ireland
- AIB Group
- Kingspan

Historical daily price data from 2015 onward is used.

## Machine Learning Approach

The project compares several machine learning models:

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

Hyperparameters are optimised using:

- GridSearchCV
- RandomisedSearchCV

## Feature Engineering

Financial indicators used include:

- Daily returns
- Rolling volatility
- Moving averages
- Momentum indicators
- Relative Strength Index (RSI)

## Portfolio Construction

Using model predictions, portfolio weights are determined by:

- Minimum volatility optimisation
- Maximum Sharpe ratio optimisation

## Evaluation Metrics

Model and portfolio performance are evaluated using:

- Accuracy
- Sharpe Ratio
- Portfolio Volatility
- Maximum Drawdown
- Annualised Return

## Key Concepts Demonstrated

- Machine learning in financial markets
- Hyperparameter optimisation
- Portfolio optimisation
- Risk management
- Cross-validation for time-series data

## Technologies Used

- Python
- Jupyter Notebook
- Scikit-learn
- Optuna
- Pandas
- NumPy
- Matplotlib

## Repository Structure

- `portfolio_optimisation.ipynb` – main modelling notebook
- `datasheet.md` – dataset documentation
- `model_card.md` – ML model documentation

---

**Author:** Steven Amet