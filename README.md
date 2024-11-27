# example-case-study--multitask-learning
## IPL extraTrees multitask learning example case study
this file (example data.csv) is for the example case study for extraTrees multitask learning the file was derived from PaDEL descriptors software (1D and 2D), 
and we have filtered out potential redundant and collinearity interaction features with low variance (variance<0.16) and high correlation (r>0.9)

# IPL-Pulmonary-Absorption-Predict

This repository contains code and data supporting the research article:

Multitask learning for predicting pulmonary absorption of chemicals

Authors: Yu-Wen Chiu, Chun-Wei Tung, Chia-Chi Wang  
Published in: Food and Chemical Toxicology, 2024 (Volume 185, Article 114453)
[DOI: 10.1016/j.fct.2024.114453]
---

## Overview

Pulmonary absorption is critical for inhalation drug delivery and toxicological assessments. This study proposed a multitask machine learning model based on the ExtraTrees algorithm to predict pulmonary absorption. By leveraging shared knowledge from three tasks (kaIPL, PappCaco2, PappCalu3), the model demonstrated robust performance with a correlation coefficient of 0.84 for kaIPL prediction in the test set.

### Features of this Repository
1. Data Preparation: Scripts for preprocessing the IPL, Caco-2, and Calu-3 datasets.
2. Feature Selection: R code for identifying the top molecular descriptors.
3. Model Construction: Implementation of multitask ExtraTrees models for prediction.
4. Visualization: Scatter plots of observed vs. predicted values for model evaluation.

---

## Citation
If you use this repository in your research, please cite:

Chiu, Y.-W., Tung, C.-W., & Wang, C.-C. (2024). Multitask learning for predicting pulmonary absorption of chemicals. Food and Chemical Toxicology, 185, 114453.  
[DOI: 10.1016/j.fct.2024.114453]
