# 🏀 Predicting NBA Player Efficiency: A Machine Learning Approach

Machine learning project predicting NBA Player Efficiency Rating (PER) using 31,000+ player-season records from 1947–2025. Applies Linear Regression and Decision Tree models alongside statistical hypothesis testing to identify key performance drivers.

## 🌐 Live Project
View the full analysis here: [NBA Player Efficiency Analysis](https://speddi5288.github.io/nba-player-efficiency/NBA.html)

## 📁 Files
- `NBA_.ipynb` — Main Jupyter notebook with full analysis
- `NBA.html` — Rendered HTML version of the notebook
- `Advanced.csv` — Dataset sourced from [Basketball Reference via Kaggle](https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats)

## 🔬 Research Questions
1. Can a player's efficiency rating be predicted from their advanced statistics?
2. Which performance metrics matter most for valuing a player?
3. How do age and position factor into player performance?

## 📊 Methods
- **Exploratory Data Analysis** — T-test, Chi-squared test, and Z-test
- **Machine Learning** — Linear Regression and Decision Tree Regressor
- **Data Preprocessing** — Handling 80,000+ missing values across 30 features

## 📈 Key Results
| Model | R² Score | RMSE |
|---|---|---|
| Linear Regression | 0.695 | 3.34 |
| Decision Tree | 0.618 | 3.74 |

- **True Shooting Percentage** is the strongest predictor of PER
- Younger players show slightly higher average efficiency
- Age and position are statistically significant but secondary to on-court performance metrics

## 🛠️ Setup
This notebook was built in **Google Colab**. To run it locally:
1. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn scipy statsmodels`
2. Update the file path in the data loading cell to point to your local `Advanced.csv`

## 🧰 Technologies
`Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib` `Seaborn` `SciPy` `Google Colab`
