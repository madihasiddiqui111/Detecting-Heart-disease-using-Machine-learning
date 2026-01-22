# Heart Disease Prediction Using Machine Learning


## Overview

This project focuses on the early prediction of heart disease using various machine learning classification models.
Since coronary heart disease is one of the leading causes of mortality worldwide, developing an accurate and reliable prediction system can significantly support preventive healthcare and early diagnosis.

The project emphasizes feature selection, model comparison, and performance evaluation to identify the most effective predictive approach.

## Objectives

The primary objectives of this project are:

* To identify significant clinical features contributing to heart disease

* To apply and compare multiple machine learning algorithms

* To evaluate model performance using robust classification metrics

* To determine the most effective model for heart disease prediction


## Dataset 

**Source:** UCI Cleveland Heart Disease Dataset

**Dataset:** UCI Machine Learning Repository

**Total Records:** 303

**Features:** 13 (excluding target variable)

### Proposed System Architecture

![Proposed System Workflow](assets/proposed_system.png)


## Data Preprocessing

### Feature Selection
The dataset contains multiple features, some of which may be irrelevant or weakly correlated with heart disease.
To improve model accuracy and reduce noise, feature selection techniques are applied.

These techniques help:

* Eliminate uninformative features

* Improve model generalization

* Reduce computational complexity



### Feature Selection Techniques Used: 

* **ANOVA (Analysis of Variance):**
  Evaluates the statistical relationship between each feature and the target variable.

* **Chi-Square Test:**
  Measures the dependence between non-negative features and the target variable.

* **Mutual Information:**
Quantifies the amount of information shared between features and the target.


  ## Classification Models
  
The following machine learning classifiers are implemented and evaluated:

* **Logistic Regression**
* **K-Nearest Neighbors (KNN)**
* **Support Vector Machine (SVM)**
* **AdaBoost**


## Evaluation Metrics

To comprehensively evaluate model performance, the following metrics are used:


* Accuracy
* Specificity
* Sensitivity (Recall)
* Area Under ROC Curve (AUROC)
*Log Loss

These metrics provide insight into both classification correctness and probabilistic confidence.

  ## Results

The experimental results demonstrate that feature selection significantly improves classification performance across all models.

 Detailed experimental results and analysis are published here:
 
 https://ieeexplore.ieee.org/document/10863677

## Technology Stack

### Language

* Python 3.12

### Libraries

* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn


  ## Future Work

Future enhancements to this project include:

* Applying the framework to larger, real-world clinical datasets

* Using live hospital data for real-time prediction

* Exploring deep learning models for improved accuracy and robustness

* Integrating the system into a clinical decision support tool



