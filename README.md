# Credit Scoring — Legacy version (2022)

> **⚠️ This is an archived version of my OpenClassrooms Data Scientist certification project from 2022.**
>
> A production-grade rebuild is currently in progress at **[mlops-credit-scoring](https://github.com/morganmadelaine/mlops-credit-scoring)** with a modern MLOps stack (BigQuery + dbt, MLflow, FastAPI, Cloud Run, CI/CD, drift monitoring with Evidently). Please refer to that repository for my current credit scoring work.

## What was this?

OpenClassrooms Data Scientist certification — Project 7: "Implémentez un modèle de scoring". A credit default risk model (LightGBM) with Flask and Streamlit interfaces for interactive predictions, deployed on Heroku.

The project used the [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) dataset and included:
- Feature engineering across multiple source tables
- Model selection with GridSearchCV (LGBM, XGBoost, Random Forest)
- Business cost function (FN weighted 10× FP)
- Flask API + Streamlit dashboard with SHAP explainability

## Why is it kept public?

For historical transparency. The new `mlops-credit-scoring` repository addresses the limitations identified in the original methodological note: no experiment tracking (MLflow), no drift monitoring, no CI/CD, no Infrastructure-as-Code, manual deployment, no unit tests.

## Stack at the time

`Python` · `scikit-learn` · `LightGBM` · `Flask` · `Streamlit` · `Heroku`

---

**Author:** Morgan Madelaine · [LinkedIn](https://www.linkedin.com/in/morgan-madelaine-pro) · morgan.madelaine1@gmail.com