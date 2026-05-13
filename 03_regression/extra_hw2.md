# AutoGluon Exploration Task — Individual Assignment

## Overview

AutoGluon is an open-source AutoML framework developed by Amazon that automates the end-to-end machine learning pipeline — from data preprocessing and feature engineering to model selection, ensembling, and hyperparameter tuning. Unlike tools such as MLJAR or DALEX explored in class, AutoGluon takes a "fit and predict" philosophy with minimal configuration, making it a compelling candidate for rapid prototyping and production deployment.

Your task is to explore AutoGluon independently, build a working demo, and critically evaluate it from both a practitioner's and an explainability perspective.

---

## Deliverables

### 1. GitHub Repository

Your repository must be clean, documented, and reproducible. It should include:

- A `README.md` with a project description, setup instructions, and a summary of findings
- A Jupyter notebook demonstrating a complete AutoGluon pipeline on a dataset of your choice (tabular classification or regression)
- A `requirements.txt` or `environment.yml` so the code can be run independently
- At least one visualization (e.g., leaderboard plot, feature importance, confusion matrix)

### 2. Medium-style Technical Article

Write a structured article of approximately 600–900 words (Markdown in the repo is fine) covering:

- What AutoGluon is and how it works conceptually
- A walkthrough of your case study: dataset choice, the problem you are solving, and what AutoGluon produced
- A comparison with at least one tool covered in class (e.g., MLJAR, DALEX, or scikit-learn pipelines)
- Your critical opinion — what are the pros and cons, and would you recommend it for a real production system? Under what conditions?

The article should read like something you would actually publish — a real case study with a story, not a lab report. The notebook should follow the same narrative, so both artifacts tell a coherent story together.

---

## Grading Criteria

| Area | Points |
|------|--------|
| Repository quality (structure, README, reproducibility) | 1 |
| Working AutoGluon implementation (fit, predict, leaderboard) | 2 |
| Article quality — clarity, structure, real insight beyond the API docs | 4 |
| Critical opinion — pros/cons and production assessment are specific and well-argued | 3 |
| **Total** | **10** |

---

## Hints and Suggestions

- AutoGluon offers several **presets** (`"best_quality"`, `"medium_quality"`, `"optimize_for_deployment"`) — try more than one and compare results
- The `leaderboard()` method is very useful for understanding what AutoGluon tried under the hood
- For an extra angle on explainability, consider wrapping AutoGluon's best model with SHAP — this ties directly to what was covered in class
- Choose a dataset with a real-world context (e.g., from UCI, Kaggle, or OpenML) so your case study has a meaningful story

---

## Submission

Submit a link to your public GitHub repository by **May 29**.