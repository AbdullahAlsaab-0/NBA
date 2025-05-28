# 🏀 NBA Shooting Data Analysis

This project analyzes NBA playoff shooting data for four players. It aims to uncover patterns in shot success, player performance, and the impact of defenders using data visualization and machine learning techniques.

---

## 📁 Dataset Overview

The dataset contains detailed information about each shot taken:

| Variable   | Description                                                   |
|------------|---------------------------------------------------------------|
| `SHOOTER`  | Name of the player taking the shot                            |
| `X`        | Horizontal distance from the basket (in feet)                 |
| `Y`        | Vertical distance from the basket (in feet)                   |
| `RANGE`    | Range category of the shot (e.g., 0–10 ft, 10–20 ft, etc.)    |
| `DEFENDER` | Name of the player defending the shot                         |
| `SCORE`    | Shot result (`MADE` or `MISSED`)                              |

---

## ❓ Key Questions Explored

- On whom would you put your best defender?
- What are the best shooting positions for each player?
- Who is the best defender?
- Is there a correlation between shooter efficiency and the defender?
- Visualize shots made and missed using scatter plots.

---

## 📊 Tools & Libraries Used

- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Machine Learning: Scikit-learn  
  (Logistic Regression, SVM, Random Forest, Neural Networks, etc.)
- Model Evaluation: ROC curves, Confusion Matrices, Calibration Curves

---

## 🚀 Highlights

- **Exploratory Data Analysis**: Patterns in shot positions and results
- **Defensive Impact**: Analyzing defender effectiveness
- **Classification Models**: Predicting shot success
- **Visual Insights**: Heatmaps and shot charts for deeper understanding

---

## 📌 Getting Started

1. Clone or download the repository.
2. Place the `nba_players_shooting.csv` dataset in the same directory as the notebook.
3. Run the notebook using Jupyter or any compatible Python environment.

---

## 📈 Sample Visual Output

- Shot scatter plots
- Heatmaps of shooting and defending zones
- ROC curves and classifier performance comparisons

---
