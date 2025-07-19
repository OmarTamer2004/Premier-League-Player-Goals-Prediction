# Premier-League-Player-Goals-Prediction
# ⚽ Premier League Goals Prediction Using Linear Regression

This project applies **Machine Learning** to predict the number of **goals** a player is likely to score in the **English Premier League (EPL)** using real match performance statistics.

---

## 📌 Project Overview

We built a **Linear Regression model** to estimate the number of goals scored by a player based on:
- Assists
- Minutes played
- Passes attempted
- xG (Expected Goals)
- xA (Expected Assists)
- Pass accuracy
- And other match stats

This project uses real data from the 2020–21 Premier League season.

---

## 🧠 Features Used

- `Age`
- `Matches`, `Starts`, `Minutes`, `MinutesPerMatch`
- `Assists`, `xG`, `xA`
- `Passes_Attempted`, `Perc_Passes_Completed`

---

## 📊 Model Results

- **Model**: Linear Regression (Scikit-learn)
- **R² Score**: ~0.60
- **Mean Absolute Error**: ~1.24 goals

---

## 📈 Visualizations Included

- Distribution of goals scored by players
- Scatter plot of Goals vs Assists (by player position)
- Correlation heatmap of all numeric performance stats

---

## 🛠️ Tech Stack

- Python (pandas, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook
- Dataset: EPL Player Stats (2020–2021 Season)

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/epl-goals-prediction.git
cd epl-goals-prediction
pip install -r requirements.txt
jupyter notebook
