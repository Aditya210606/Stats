# Experiment 04 – Statistical Inference, Estimation and Hypothesis Testing

## Title

**Perform Statistical Inference, Estimation, and Hypothesis Testing on Real-World Datasets**

## Aim

To apply statistical estimation and hypothesis testing techniques to the **Pima Indians Diabetes Dataset** and draw conclusions about population characteristics using sample data.

## Objectives

After completing this experiment, the following objectives were achieved:

1. Applied statistical estimation techniques to analyze population characteristics.
2. Constructed confidence intervals for selected population parameters.
3. Formulated null and alternative hypotheses.
4. Applied suitable statistical tests to the dataset.
5. Calculated test statistics and p-values.
6. Interpreted statistical results and made data-driven conclusions.

## Tools and Technologies Used

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn

## Dataset

**Dataset:** Pima Indians Diabetes Dataset

The dataset contains diagnostic information for **768 female patients**.

The dataset includes medical attributes such as glucose level, blood pressure, BMI, age, and other health-related measurements that can be used for statistical analysis.

## Methodology

The experiment follows the workflow:

```text
Dataset
   ↓
Data Selection
   ↓
Point Estimation
   ↓
Confidence Interval
   ↓
Hypothesis Formulation
   ↓
Statistical Test
   ↓
Test Statistic and P-Value
   ↓
Statistical Decision
   ↓
Interpretation
```

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select suitable variables for statistical analysis.
3. Calculate point estimates such as sample mean and sample proportion.
4. Construct confidence intervals for selected parameters.
5. Formulate the null and alternative hypotheses.
6. Select an appropriate statistical test.
7. Calculate the test statistic and p-value.
8. Compare the p-value with the selected significance level.
9. Make a statistical decision based on the test result.
10. Interpret the results obtained from the statistical analysis.

## Statistical Methods Used

### Point Estimation

Point estimation uses a sample statistic to estimate an unknown population parameter. The sample mean and sample proportion can be used to estimate corresponding population parameters.

### Confidence Interval

A confidence interval provides a range of plausible values for a population parameter based on sample data. It helps represent the uncertainty associated with an estimated parameter.

### Hypothesis Testing

Hypothesis testing is used to examine a claim about a population.

The experiment uses:

* **Null Hypothesis (H₀):** Initial assumption being tested.
* **Alternative Hypothesis (H₁):** Claim being investigated.

A significance level such as **α = 0.05** is used for making the statistical decision.

## Statistical Tests

### One-Sample t-Test

A one-sample t-test is used to compare a sample mean with a specified reference value.

### Two-Sample t-Test

A two-sample t-test is used to compare the means of two independent groups.

### Chi-Square Test

The Chi-Square test is used to determine whether an association exists between categorical variables.

## P-Value and Decision

The p-value indicates the strength of evidence against the null hypothesis.

The general decision rule is:

```text
If p-value < 0.05
       ↓
Reject H₀

If p-value ≥ 0.05
       ↓
Fail to Reject H₀
```

The final conclusion is based on the statistical test and the obtained p-value.

## Results

The experiment successfully:

* Calculated statistical estimates from the dataset.
* Constructed confidence intervals.
* Formulated null and alternative hypotheses.
* Applied suitable statistical tests.
* Calculated test statistics and p-values.
* Interpreted the statistical results.

## Conclusion

Statistical inference techniques were successfully applied to the Pima Indians Diabetes Dataset. Point estimation and confidence intervals were used to analyze population characteristics, while hypothesis testing was used to examine statistical claims. The experiment demonstrated how sample data can be used to perform statistical analysis and draw meaningful conclusions about a population.

# Screenshots:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/65b05e26-b566-4621-8cde-40a7cdf1bc16" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/71591f7d-1431-4c7a-86b3-65234f3a80b0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9d447358-f3a2-4e92-86e8-edc87935795a" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8afc4bda-f5b1-4796-a8e9-f339237b9f5a" />

