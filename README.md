# IPL ExtraTrees Multitask Learning - Example Case Study  

This repository provides code and data for an example case study of multitask learning using the ExtraTrees algorithm. The included dataset (`example_data.csv`) was derived from **PaDEL Descriptors Software (1D and 2D)**. Features with low variance (<0.16) and high correlation (r > 0.9) were filtered to reduce redundancy and collinearity.  

---

## IPL-Pulmonary-Absorption-Predict  

This repository supports the research article:  

**Multitask Learning for Predicting Pulmonary Absorption of Chemicals**  
**Authors**: Yu-Wen Chiu, Chun-Wei Tung, Chia-Chi Wang  
**Published in**: *Food and Chemical Toxicology*, 2024 (Volume 185, Article 114453)  
[DOI: 10.1016/j.fct.2024.114453](https://doi.org/10.1016/j.fct.2024.114453)  

---

## Overview  

Pulmonary absorption plays a critical role in inhalation drug delivery and toxicological assessments. This study introduces a multitask machine learning model, based on the **ExtraTrees algorithm**, to predict pulmonary absorption. By sharing knowledge across three tasks—**kaIPL**, **PappCaco2**, and **PappCalu3**—the model achieves robust performance with a correlation coefficient of 0.84 for kaIPL predictions in the test set.  

---

## Features of This Repository  

1. **Data Preparation**:  
   - Scripts for preprocessing the IPL, Caco-2, and Calu-3 datasets.  

2. **Feature Selection**:  
   - R code for identifying top molecular descriptors.  

3. **Model Construction**:  
   - Implementation of multitask ExtraTrees models for predictions.  

4. **Visualization**:  
   - Scatter plots of observed vs. predicted values for model evaluation.  

---

## Citation  

If you use this repository in your research, please cite:  

**Chiu, Y.-W., Tung, C.-W., & Wang, C.-C. (2024).**  
**Multitask learning for predicting pulmonary absorption of chemicals.**  
*Food and Chemical Toxicology, 185,* Article 114453.  
[DOI: 10.1016/j.fct.2024.114453](https://doi.org/10.1016/j.fct.2024.114453)  
