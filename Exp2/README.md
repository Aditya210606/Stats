# Experiment 02 – Bootstrap and Permutation Resampling

## Title

**Apply Bootstrap and Permutation Resampling Techniques for Statistical Analysis**

## Aim

To implement bootstrap and permutation resampling techniques on the **Pima Indians Diabetes Dataset** for estimating confidence intervals and analyzing statistical differences between groups.

## Objectives

After completing this experiment, the following objectives were achieved:

1. Applied bootstrap resampling to estimate sampling distributions.
2. Constructed confidence intervals using bootstrap samples.
3. Applied permutation testing to compare differences between groups.
4. Analyzed the distribution obtained from repeated resampling.
5. Interpreted the statistical results obtained from the resampling techniques.

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

The dataset contains diagnostic information for **768 female patients**. The `Outcome` variable indicates whether a patient is diabetic or non-diabetic.

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
5. Construct a confidence interval from the bootstrap distribution.
6. Divide the data into groups based on the diabetes outcome.
7. Calculate the observed difference between the group means.
8. Randomly permute the group labels repeatedly.
9. Calculate the difference for each permutation.
10. Compare the observed difference with the permutation distribution and interpret the result.

## Statistical Methods Used

### Bootstrap Resampling

Bootstrap resampling repeatedly creates samples from the original dataset with replacement. A statistic such as the mean is calculated for each sample, producing a sampling distribution.

This distribution can be used to estimate the variability of the statistic and construct a confidence interval.

### Permutation Test

A permutation test evaluates whether an observed difference between two groups could have occurred by chance.

The group labels are randomly shuffled repeatedly, and the difference between group statistics is calculated for each permutation. The resulting distribution is used for statistical comparison.

## Confidence Interval

A bootstrap confidence interval provides a range of plausible values for a population parameter based on the bootstrap sampling distribution.

A **95% confidence interval** can be obtained using the appropriate percentiles of the bootstrap distribution.

## Results

The experiment successfully:

* Generated bootstrap samples from the dataset.
* Created a bootstrap sampling distribution.
* Estimated a confidence interval for the selected statistic.
* Performed a permutation test between groups.
* Analyzed the permutation distribution.
* Interpreted the obtained statistical results.

## Conclusion

Bootstrap and permutation resampling techniques were successfully applied to the Pima Indians Diabetes Dataset. Bootstrap resampling was used to estimate the sampling distribution and confidence interval of a selected statistic, while permutation testing was used to analyze differences between groups. The experiment demonstrated how resampling methods can be used for statistical estimation and hypothesis analysis.

---

# Screenshots

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8bd522ae-28c4-43a2-8842-46af459651d4" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9bfe1cd6-8567-4356-9812-535e56e97c30" />
