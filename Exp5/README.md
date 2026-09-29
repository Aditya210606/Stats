# Experiment 05 – Resampling Techniques and Confidence Interval Estimation

## Title

**Implement Resampling Techniques and Confidence Interval Estimation for Statistical Decision Making**

## Aim

To implement bootstrap and permutation resampling techniques on the **Pima Indians Diabetes Dataset** for estimating confidence intervals and analyzing statistical differences between groups.

## Objectives

After completing this experiment, the following objectives were achieved:

1. Applied bootstrap resampling to estimate sampling distributions.
2. Estimated confidence intervals using bootstrap samples.
3. Applied permutation testing to compare two groups.
4. Analyzed statistical differences between diabetic and non-diabetic groups.
5. Interpreted resampling results for statistical decision making.

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

The target variable is:

* `Outcome = 0` → Non-diabetic
* `Outcome = 1` → Diabetic

## Methodology

The experiment follows the workflow:

```text
Dataset
   ↓
Data Selection
   ↓
Bootstrap Resampling
   ↓
Sampling Distribution
   ↓
Confidence Interval
   ↓
Group Formation
   ↓
Permutation Test
   ↓
Statistical Comparison
   ↓
Interpretation
```

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select a numerical variable such as Glucose or BMI.
3. Generate repeated bootstrap samples with replacement.
4. Calculate the selected statistic for each bootstrap sample.
5. Construct the bootstrap confidence interval.
6. Divide the dataset into two groups based on the Outcome variable.
7. Calculate the observed difference between group means.
8. Randomly permute the group labels repeatedly.
9. Generate the permutation distribution.
10. Compare the observed difference with the permutation distribution.

## Bootstrap Resampling

Bootstrap is a resampling technique in which multiple samples are created from the original dataset by sampling **with replacement**.

For each bootstrap sample, a statistic such as the mean is calculated. The collection of these values forms an approximate sampling distribution.

A confidence interval can then be estimated from this distribution. In this experiment, a **95% bootstrap confidence interval** was used.

## Permutation Test

A permutation test is used to determine whether an observed difference between two groups could have occurred by chance.

In this experiment, the data was divided into diabetic and non-diabetic groups. The group labels were randomly shuffled repeatedly, and the difference between group means was calculated for each permutation.

The resulting values form a **permutation distribution**, which is used to evaluate the statistical significance of the observed difference.

## Statistical Analysis

The experiment mainly uses:

### Bootstrap Confidence Interval

The bootstrap distribution is used to estimate the range within which the population statistic is expected to lie.

### Difference in Group Means

The difference between the mean values of the two groups is calculated to understand their statistical difference.

### Permutation p-value

The p-value obtained from the permutation distribution is used to determine whether the observed group difference is statistically significant.

## Results

The experiment successfully:

* Generated bootstrap samples from the dataset.
* Obtained a bootstrap sampling distribution.
* Estimated a 95% confidence interval for mean Glucose.
* Compared mean Glucose between diabetic and non-diabetic groups.
* Generated a permutation distribution.
* Evaluated the statistical significance of the observed difference.

The mean Glucose was approximately **120.89 mg/dL**, with a 95% bootstrap confidence interval of approximately **116–125 mg/dL**. The observed difference in mean Glucose between the groups was approximately **31.28 mg/dL**.

## Conclusion

Bootstrap and permutation resampling techniques were successfully implemented on the Pima Indians Diabetes Dataset. Bootstrap resampling was used to estimate the sampling distribution and confidence interval, while permutation testing was used to analyze the statistical difference between diabetic and non-diabetic groups. The experiment demonstrated how resampling techniques can support statistical analysis and decision making.

---

# Screenshots

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9f2eaf54-f65e-421c-887a-ffb076d673bd" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3c4b0966-f73e-468a-9e2c-733c1e2fb9a3" />

