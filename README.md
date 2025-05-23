# 🧪 Drug Failure Prediction Using Synthetic Data

This project simulates drug discovery data and predicts potential drug failure using **machine learning models** (Logistic Regression and Decision Tree). It focuses on analyzing the impact of key pharmacokinetic and toxicity parameters on drug trial outcomes.

## 📊 Project Overview

We use synthetic data to represent critical properties such as:

- Molecular weight
- Solubility
- Bioavailability
- Toxicity score
- hERG channel inhibition
- CYP450 inhibition
- Liver enzyme elevation
- Plasma protein binding

A failure probability is simulated based on threshold rules. Then, we use **ML models** to predict whether a drug will **pass** or **fail** based on these features.

## 📁 Files

- `drug_failure_prediction.ipynb` — Complete notebook with data generation, visualization, and model building.
- `README.md` — This file.

## 🚀 How to Use

1. Clone this repository or download the notebook.
2. Open `drug_failure_prediction.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells to see data generation, visualizations, and ML results.

## 📈 Results

- **Logistic Regression** and **Decision Tree** are trained on the synthetic dataset.
- Evaluation is done using classification reports.
- Feature importance is visualized for interpretability.
- Clear bar plots compare average property values between failed and passed drugs.

## 📌 Key Insights

- Drugs with high **toxicity scores** and **low solubility** are more likely to fail.
- **hERG inhibition** and **bioavailability** also significantly affect failure probability.
- Visual analysis and simple ML can help identify patterns before costly trials.

## 📚 Libraries Used

- `NumPy`, `Pandas`
- `Matplotlib`, `Seaborn`
- `Scikit-learn`

---

🧠 *This is a synthetic project for educational purposes and is not based on real clinical data.*
