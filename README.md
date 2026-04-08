# AIM AHEAD Cohort Analysis (TAG)

## Background

This project is part of the **AIM-AHEAD (Artificial Intelligence/Machine Learning Consortium to Advance Health Equity and Researcher Diversity)** initiative, a national effort supported by the National Institutes of Health (NIH) and the National Center for Advancing Translational Sciences (NCATS). AIM-AHEAD aims to improve the development and application of artificial intelligence and machine learning models in healthcare while promoting health equity and increasing diversity in the research workforce.

Our team is participating in this initiative through a collaborative, cohort-based data science project focused on real-world clinical data.

---
## Research Question

Among adults with documented substance use disorder (SUD), can machine learning identify multimorbidity phenotypes, and are these phenotypes associated with higher prevalence of recorded mortality?

## Project Overview

The goal of this project is to explore and analyze a large, real-world healthcare dataset in order to:

- Characterize the analytic cohort
- Identify meaningful clinical and demographic patterns
- Evaluate data quality and missingness
- Develop a defensible feature selection pipeline
- Prepare data for predictive modeling

This work emphasizes **reproducibility**, **interpretability**, and **methodological rigor**, with a focus on building models that are both clinically meaningful and statistically sound.

---

## Research Focus

Our specific research focus is:

> *To evaluate how patient-level characteristics (e.g., demographics, comorbidities, and behavioral factors) are associated with key clinical outcomes within the AIM AHEAD cohort.*

Particular attention is given to:
- The role of comorbid conditions
- The interaction of demographic and behavioral risk factors
- Potential disparities across population subgroups

---

## Analytic Plan

Our analytic approach follows a structured pipeline:

### 1. Exploratory Data Analysis (EDA)
- Examine distributions of key variables
- Identify outliers and inconsistencies
- Evaluate cohort composition
- Assess missingness patterns

### 2. Data Quality Assessment
- Quantify missing data across variables
- Identify non-random missingness
- Evaluate variable reliability and consistency

### 3. Variable Selection
We use a hybrid approach combining:
- **Theory-driven selection** (clinical relevance and causal reasoning)
- **Data-driven screening** (missingness, variance, redundancy)
- **Correlation analysis** to reduce multicollinearity
- **Model-based selection** (regularization methods such as LASSO)

### 4. Dataset Preparation
- Clean and preprocess variables
- Encode categorical features
- Address missing data (e.g., imputation strategies)

---

## Machine Learning Approach

We plan to apply machine learning methods to develop predictive models for key outcomes within the cohort.

### Planned techniques include:
- Regularized regression (LASSO, Ridge)
- Tree-based models (Random Forest, Gradient Boosting)
- Model evaluation using cross-validation

### Key priorities:
- **Interpretability** (understanding which variables drive predictions)
- **Generalizability** (robust performance across subsets of data)
- **Bias awareness** (evaluating model performance across demographic groups)

This approach ensures that modeling efforts align with both **clinical insight** and **ethical considerations in AI**.

---


---

## Tools and Technologies

- Python (pandas, numpy, scikit-learn)
- Jupyter Notebooks
- Data visualization (matplotlib, seaborn, plotnine)

---

## Data Availability

Due to data use agreements and privacy considerations, the raw dataset is not included in this repository. All code is provided to ensure transparency and reproducibility of the analytic workflow.

---

## Team

This project was completed by:

- Todd Adams, Ph.D. student, The University of Arizona
- Maya Foster, Ph.D. student, Yale University
- Allison Ihle, Ph.D., UT Health San Antonio
- Taylor Krajewski. Ph.D., Duke University
- Carlo Lutz, MD, Ph.D., Albert Einstein College of Medicine
- Dmitry Shcherbakov, Ph.D, Medical University of South Carolina

---

## Future Directions

- Development and validation of predictive models
- Sensitivity analyses for missing data
- Exploration of subgroup-specific effects
- Expansion of feature engineering and model refinement

---

## Notes

This repository reflects a structured, reproducible approach to applied data science in healthcare, integrating domain knowledge with modern machine learning techniques.
