Dataiku Data Scientist Technical Assessment

This repository contains a technical solution for the Dataiku Data Scientist position, based on a sample dataset from the U.S. Census Bureau.

## Objective

To identify characteristics that are associated with a person making more or less than $50,000 per year using a combination of data analysis and machine learning.

## Approach

The notebook walks through a full data science pipeline:

1. Exploratory Data Analysis (EDA):
   - Distributions, class balance, categorical breakdowns
   - Correlation checks and feature exploration

2. Data Cleaning & Preprocessing:
   - Handling missing values
   - Encoding categorical variables
   - Binning continuous variables

3. Model Building:
   - Train/test split
   - Initial modeling using Random Forest
   - Testing K-Nearest Neighbours
   -  

4. Model Evaluation:
   - Accuracy
   - ROC-AUC
   - precision
   - recall
   - Classification reports
   - Models comparison

## Reproducibility & Requirements

- All steps are included in the notebook for reproducibility.
- To run this notebook, you can use the following environment:

```bash
pip install -r requirements.txt
```

If no `requirements.txt` is present, install the basics:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Files

-  dataiku_assignment.ipynb — production-oriented notebook
-  assignment slides
-  README.md — this file
-  requirements.txt

## 📝 Notes

- This notebook focuses on creating a solid and interpretable model.
- Additional improvements like hyperparameter tuning or alternative models (e.g., KNN, XGBoost) can be added as extensions.

---

Feel free to explore and reach out with any questions!

