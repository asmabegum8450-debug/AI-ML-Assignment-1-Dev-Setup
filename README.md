# AI-ML Assignment 1: Iris Data Exploration  
**Author:** Asma Begum

---

## Environment & Dependencies
Final versions used in this project:

- **Python:** 3.11
- **pandas:** 2.1.0
- **numpy:** 1.26.0
- **matplotlib:** 3.8.0
- **seaborn:** 0.13.0
- **scikit-learn:** 1.3.1
- **jupyter:** 1.0.0

---

## Summary of Key Findings
From the exploratory data analysis (EDA) of the Iris dataset:

- **Petal length and petal width are the strongest features** for separating species.
  - *Setosa* is clearly separable due to very small petal length/width.
  - *Versicolor* vs *Virginica* separate better when using **petal width** (and length) together.
- **Sepal measurements** (length/width) show **substantial overlap** between classes and are weaker as standalone predictors.
- **Correlation**: petal length and petal width are both highly correlated with species labels and with each other.
- A simple baseline (e.g., **Logistic Regression** with petal features) reaches **~95–97% accuracy** on a hold-out split.

---

## Files
- `iris_exploration.ipynb` — Notebook with EDA code, plots, and a quick baseline model.
- `README.md` — This file.

---

## How to Run
1. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate      # Windows: .venv\Scripts\activate
