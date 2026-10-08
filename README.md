# Project 3: Support Vector Machines and Decision Tree Ensembles

CS-4103 Fundamentals of Machine Learning, University of Tulsa

## What is here

- `assignment/Assignment 3.1.ipynb` and `assignment/Assignment 3.2.ipynb`, the two notebooks you complete. 3.1 covers support vector machines on four two-feature datasets. 3.2 covers a single decision tree, random forests, AdaBoost, and XGBoost on the handwritten digits and German Credit datasets.
- `data/`, the Linear Separable, Ellipse, and Spirals synthetic datasets, the Breast Cancer Wisconsin subset, and German Credit. The digits dataset comes with scikit-learn.
- `assignment/Project 3 - Support Vector Machines and Decision Tree Ensembles.pdf`, the project spec. The same PDF is posted on Harvey.

Sources: Breast Cancer Wisconsin (Diagnostic) and Statlog (German Credit Data) are from the UCI Machine Learning Repository. The Breast Cancer data keeps two of its 30 features, worst area and worst smoothness, standardized.

## Setup

Use Python 3.10 or newer.

```
pip install -r requirements.txt
jupyter notebook
```

Open the notebooks from the `assignment` folder. They load data through `../data`, so they fail if you move them or start them elsewhere.

## Working in the notebooks

Every algorithm in this project comes from a library: scikit-learn for the support vector machines, the decision tree, random forest, and AdaBoost, and xgboost for XGBoost. The cross-validation search and the accuracy functions are already written. Your job is to configure each model with the right arguments, call the provided functions with the right settings, and write about what you see.

Fill in each `TODO`. The numbered comment above a `TODO` lists the steps that region needs.

Import nothing beyond the libraries listed in the import cell.

Run every cell, top to bottom, before you submit. 3.2 takes a few minutes, most of it on the digits dataset.

## Submitting

Submit through Harvey:

- Both notebooks, with all outputs visible.
- The report PDF described in the spec.

A notebook with cleared outputs is graded as though the code did not run.
