# ML Fairness Audit (UCI Adult)

This project explores the topic of **bias and fairness in Machine Learning** using the **UCI Adult** dataset.  
It provides familiarity with the concept of bias in ML, explores different metrics to quantify bias, and demonstrates **data- and model-based** approaches to audit bias and fairness in ML.

## What this notebook does
- Loads and prepares **UCI Adult** (income > $50K).
- Trains simple baselines: **Logistic Regression**, **Random Forest**, **Naive Bayes**, **MLP**, **SVC**, and **Voting** (hard/soft).
- Audits fairness by a sensitive attribute (**`sex`**, optional `race`) with:
  - **Demographic Parity (DP)** & **Disparate Impact (DI)**
  - **Equal Opportunity** (TPR gap) & **Equalized Odds** (TPR/FPR gaps)
- Applies a **model-based post-processing** mitigation (**group-specific thresholds**) and compares **before/after** metrics.  







