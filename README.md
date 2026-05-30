# 🍽️ Restaurant Revenue Prediction

A regression project that predicts restaurant revenue using Linear Regression, with PCA applied for dimensionality reduction and comparison.

## 📊 Results

| Model | R² Score |
|-------|----------|
| Linear Regression | 86.22% |
| Linear Regression after PCA | 84.47% |

> PCA slightly reduced accuracy but significantly simplified the feature space, demonstrating the accuracy vs. complexity trade-off.

## 📁 Project Structure

```
restaurant-revenue-model/
│
├── restaurant_revenue.ipynb   # Main notebook
├── restaurant_revenue(1)(1).csv   # Dataset
└── README.md
```

## 🔍 Approach

1. **Data Cleaning** — Handled missing values and prepared features
2. **EDA** — Explored key factors influencing restaurant revenue
3. **Modelling** — Trained a Linear Regression model using Scikit-learn
4. **PCA** — Applied Principal Component Analysis to reduce dimensionality
5. **Comparison** — Evaluated model performance before and after PCA

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (LinearRegression, PCA)

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/mdsajid4626/restaurant-revenue-model
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open the notebook
   ```bash
   jupyter notebook restaurant_revenue.ipynb
   ```

## 👤 Author

**Mohammed Sajid**  
[LinkedIn](www.linkedin.com/in/mohammmed-sajid-47b92131b) | [GitHub](https://github.com/mdsajid4626)