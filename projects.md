---
layout: default
title: Projects
---

# Projects
Each project includes: **problem → data → approach → validation → results → what I’d do next**.

---

## <a id="loan-default"></a> Loan Default Prediction
**Goal:** Predict probability of default for loan applications.  
**Key skills:** preprocessing, feature engineering, model selection, evaluation, reproducibility.

- **Data:** Kaggle loan dataset (tabular, mixed types)
- **Approach:** baseline → tree models → ensembles; pipeline with consistent preprocessing
- **Validation:** stratified split, leakage checks, ROC-AUC / PR-AUC, calibration
- **Result:** (add your metric + comparison, e.g. “+35% ROC-AUC vs baseline”)
- **Repo:** YOUR_REPO_LINK

**What I’d do next**
- Calibrate probabilities, add drift monitoring plan, and package as a small service.

---

## <a id="churn"></a> Customer Churn Risk Modeling
- **Goal:** rank customers by churn risk for retention prioritization
- **Highlights:** feature leakage prevention, time-based splits (if applicable), explainability (SHAP)

**Repo:** YOUR_REPO_LINK

---

## <a id="soccer"></a> Soccer Usage Analytics
- **Goal:** translate NBA “usage rate” philosophy to soccer to quantify player involvement + projection
- **Tech:** Streamlit, Pandas, Plotly/Matplotlib, (optional) PySpark

**Repo:** YOUR_REPO_LINK

---

## <a id="outliers"></a> Outlier Detection Pipeline
- **Goal:** compare outlier methods and quantify impact on downstream model performance
- **Methods:** isolation forest, robust z-score, DBSCAN/LOF, winsorization strategies
- **Deliverable:** “method selection guide” + reproducible evaluation notebook

**Repo:** YOUR_REPO_LINK
