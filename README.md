# Statistical Analysis of Clinical Risk Factors Associated with Heart Disease

This repository contains a comprehensive statistical analysis of clinical cardiovascular data, aimed at identifying key determinants of heart disease and evaluating their diagnostic significance. The study is based on a dataset of 1,190 observations.

## Key Findings
* **Age & Cholesterol:** Identified as the strongest positive predictors of heart disease. Logistic regression analysis confirmed a significant risk increase as age progresses ($p < 0.001$).
* **Maximum Heart Rate:** Exhibits a strong inverse correlation with disease probability, serving as a critical marker for cardiovascular efficiency.
* **Symptomatic Indicators:** "Asymptomatic" (Type 4) chest pain was found to be the most dominant clinical marker for a positive diagnosis.
* **Gender Dimorphism:** In the diseased population, female patients maintain a statistically higher heart rate capacity (mean: 139.44 bpm) compared to male patients (mean: 128.57 bpm), despite the presence of pathology ($p = 0.00028$).

## Methodology
The research employs a multi-modal statistical approach to validate hypotheses:
* **Logistic Regression:** Used to model the relationship between age/heart rate and disease probability.
* **Independent Samples T-Test:** Used to compare cholesterol levels and gender-based heart rate capacities.
* **Chi-Square Test of Independence:** Used to analyze the correlation between chest pain types and diagnostic outcomes.
* **Pearson Correlation:** Used to determine linear interactions between physiological variables.

## Mathematical Modeling
The relationship between age and the probability of heart disease was modeled using the following logistic regression formula:
$$\text{logit}(P) = -3.0772 + 0.0595 \times \text{Age}$$
The model's significance was verified with a p-value of $1.77 \times 10^{-18}$.

## Project Structure
* `Statistics_Report.pdf`: The full research paper including detailed methodology, data visualizations (boxplots, heatmaps, sigmoid curves), and comprehensive references.

---
*This study was conducted by Umut Ali Arslan as part of the academic curriculum at Galatasaray University.*
