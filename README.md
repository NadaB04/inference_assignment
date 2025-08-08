# Sleep Efficiency Analysis: Caffeine and Alcohol Consumption

## Overview
This analysis explores the relationship between caffeine consumption, alcohol consumption, and sleep quality using a dataset of sleep patterns.  
The dataset includes multiple sleep-related features, and the primary focus is on the **Sleep total quality**, which is calculated as:

> Sleep total quality = Sleep duration × Sleep efficiency

The analysis covers several statistical methods, including descriptive statistics, normality tests, confidence intervals, hypothesis tests, and regression analysis.

---

## Key Points
- Various normality tests were performed (Shapiro–Wilk, KS test, Anderson–Darling) to assess the distribution of sleep quality across different groups.
- **T-tests**, **Wilcoxon tests**, and **ANOVA** were used to compare sleep quality between groups.
- Regression analysis was conducted to examine the effect of caffeine consumption on sleep quality.

---

## Requirements
To run this analysis, ensure you have the following Python libraries installed:

- pandas  
- numpy  
- scipy  
- matplotlib  
- seaborn  
- statsmodels  
```bash
You can install them using pip:
pip install pandas numpy scipy matplotlib seaborn statsmodelsp
```
---

## Files
Sleep_Efficiency.csv: The dataset used for the analysis.
Contains information on sleep duration, efficiency, caffeine/alcohol consumption, and other factors.

---
## How to Run the Analysis
1. Clone this repository or download the notebook.
2. Ensure the dataset Sleep_Efficiency.csv is available in the same directory as the notebook.
3. Execute each code cell in the notebook sequentially to reproduce the analysis.

