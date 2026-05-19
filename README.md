# A/B Testing Landing Page Analysis

## Business Question

Did the new landing page improve user conversion rates compared to the existing landing page?

---

## Project Overview

This project analyzes an A/B testing experiment using statistical hypothesis testing and logistic regression.

The goal was to evaluate whether a newly designed landing page produced a meaningful improvement in conversion rate.

The analysis focuses on:

* experiment validation
* conversion rate comparison
* statistical significance
* confidence intervals
* practical interpretation of results

---

## Dataset

The dataset contains user-level experiment data including:

* assigned experiment group
* landing page version
* conversion outcome
* country information

Misaligned experiment records were removed before analysis to preserve the integrity of the A/B test structure.

---

## Methods Used

* Data Cleaning & Validation
* Exploratory Data Analysis (EDA)
* Two-Proportion Z-Test
* Confidence Interval Analysis
* Sample Size & MDE Evaluation
* Logistic Regression
* Country Interaction Analysis

---

## Key Findings

* The observed conversion difference between the treatment and control groups was very small.
* The hypothesis test did not show statistically significant evidence that the new page improved conversions.
* The confidence interval included zero, suggesting the true treatment effect may be negligible.
* Logistic regression analysis showed that country differences did not materially change the experiment conclusion.

---

## Final Conclusion

Based on the current experiment results, there is insufficient evidence to recommend replacing the existing landing page with the new version.

The analysis suggests that the new page did not produce a statistically or practically meaningful improvement in conversion performance.

---

## Tools Used

* Python
* Pandas
* NumPy
* Statsmodels
* Matplotlib
* Jupyter Notebook

---

## Visualization

### 95% Confidence Interval of Treatment Effect

![CI Chart](Confidence%20Interval%20for%20Conversion%20Rate%20Difference.png)


## Project Context

This is a personal portfolio project created using a publicly available A/B testing dataset from Kaggle to practice experiment analysis and statistical inference in a business context.
