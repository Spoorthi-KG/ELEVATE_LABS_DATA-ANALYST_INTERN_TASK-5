# ELEVATE_LABS_DATA-ANALYST_INTERN_TASK-5
# Titanic Dataset – Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using **Python (Pandas, Matplotlib, Seaborn)**.
The goal is to extract meaningful insights about passenger survival based on gender, age, class, fare, and embarkation port.

---

## 📂 Project Structure

```
.
├── Titanic train dataset.csv   # Original dataset
├── Titanic_EDA.ipynb           # Jupyter Notebook with code & visuals
├── Titanic_EDA_Report.pdf      # Final PDF report with observations
└── README.md                   # Project documentation
```

---

## ⚙️ Tools & Libraries

* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🚀 How to Run

1. Clone or download this repository.
2. Install required libraries:

   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Titanic_EDA.ipynb
   ```
4. Run the cells to reproduce the analysis and visualizations.

---

## 📊 Key Steps in EDA

* **Data Understanding:** `.info()`, `.describe()`, missing value checks
* **Univariate Analysis:** Histograms, countplots (Age, Gender, Class, Survival)
* **Bivariate Analysis:** Survival vs Gender, Class, Embarked, Fare
* **Multivariate Analysis:** Scatterplots, correlation heatmap, pairplots
* **Observations:** Notes added after each visualization

---

## 🔎 Insights from the Analysis

* Females had much higher survival rates (~74%) than males (~19%).
* 1st class passengers had the highest survival rate, 3rd class the lowest.
* Children and passengers paying higher fares were more likely to survive.
* Passengers from Cherbourg (C) had higher survival chances compared to S and Q.
* Strong survival predictors: **Gender, Passenger Class, Fare**.

---

## 📝 Deliverables

* **Jupyter Notebook (`.ipynb`)** – Full analysis with code, visuals, and observations.
* **PDF Report (`Titanic_EDA_Report.pdf`)** – Summarized findings with observations and insights.

---

## ✅ Summary

This EDA highlights how **socio-economic status, gender, and age** played major roles in Titanic survival.
The dataset confirms historical accounts that **“women and children first”** significantly influenced survival rates.

---
