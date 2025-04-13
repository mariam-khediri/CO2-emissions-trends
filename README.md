
# 🌍 Analyzing Global CO₂ Emissions Trends

## 📌 Project Overview

This project aims to explore, visualize, and model global **CO₂ emissions trends** using publicly available data. It walks through the full data analysis lifecycle, from **data cleaning** and **exploratory data analysis (EDA)** to building an interactive **dashboard** and implementing **machine learning models** for CO₂ prediction.

---

## 🎯 Objectives

- Understand **global and country-specific** CO₂ emission patterns.
- Identify **top emitters** and **emission inequalities**.
- Explore the **relationship between GDP, population, and emissions**.
- Highlight **success stories** of countries reducing emissions.
- Develop a **dashboard** for interactive data exploration.
- Build and compare **regression models** to predict future emissions.

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- Jupyter Notebook
- Voila (for dashboard rendering)
- Scikit-learn, XGBoost
- Git & GitHub

---

## 📊 Exploratory Data Analysis (EDA)

We explored the dataset by:
- Visualizing global and country-specific emission trends.
- Analyzing emissions per capita.
- Comparing emissions vs. GDP.
- Identifying major contributors to CO₂ emissions.
- Zooming in on **Tunisia** as a case study.

---

## 📈 Machine Learning Modeling

We trained multiple regression models to predict CO₂ emissions:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

**Metrics used**:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Score

---

## 🧪 Results Snapshot

| Model              | MAE   | MSE      | R²     |
|-------------------|-------|----------|--------|
| Linear Regression | 29.89 | 7385.41  | 0.9981 |
| Random Forest     | 10.61 | 2587.46  | 0.9993 |
| Gradient Boosting | 20.51 | 5353.98  | 0.9986 |
| XGBoost           | 16.56 | 19651.11 | 0.9949 |

---

## 📊 Dashboard

An interactive dashboard was created using **Voila + Plotly** to visualize trends in an engaging way.

---

## 🇹🇳 Tunisia Mini Case Study

We focused on Tunisia to:
- Analyze when emissions peaked.
- Explore its GDP-emissions trends.
- Understand emission behavior over time.

---

## 📌 How to Run

1. Clone the repo.
2. Open `Analyzing_Global_CO2_Emissions_Trends.ipynb`.
3. To launch the dashboard:
   ```bash
   voila Analyzing_Global_CO2_Emissions_Trends.ipynb
   ```

---

## 📁 Dataset

Data source: [Our World in Data](https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions)

---

## 📬 Contact

For questions, reach me at: **[mariamkhediri1@gmail.com]**

---
