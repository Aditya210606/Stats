# Experiment 01 – Exploratory Statistical Analysis

## Title

**Perform Exploratory Statistical Analysis of a Real-World Dataset (Case Study)**

## Aim

To perform exploratory statistical analysis of the **Pima Indians Diabetes Dataset** by examining its structure, variable types, data quality, statistical characteristics, and important patterns.

## Objectives

After completing this experiment, the following objectives were achieved:

1. Applied exploratory data analysis techniques to understand the structure of a real-world dataset.
2. Examined variable types and statistical characteristics.
3. Identified missing or potentially invalid values.
4. Identified potential outliers using statistical techniques and visualizations.
5. Generated visualizations to understand variable distributions and relationships.
6. Interpreted important patterns observed in the dataset.

## Tools and Technologies Used

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Dataset

**Dataset:** Pima Indians Diabetes Dataset

The dataset contains diagnostic information for female patients and is used to study factors associated with diabetes.

The dataset contains **768 observations, 8 input attributes, and one binary outcome variable**.

## Methodology

The experiment follows the workflow:

```text
Dataset
   ↓
Data Inspection
   ↓
Variable Identification
   ↓
Data Quality Analysis
   ↓
Statistical Summary
   ↓
Outlier Analysis
   ↓
Data Visualization
   ↓
Pattern Identification
   ↓
Interpretation
```

## Procedure

1. Load the Pima Indians Diabetes Dataset into a Pandas DataFrame.
2. Examine the dimensions, columns, data types, and sample records.
3. Identify numerical, categorical, and binary variables.
4. Generate a statistical summary of the dataset.
5. Check for missing or potentially invalid values.
6. Identify potential outliers using suitable techniques and visualizations.
7. Generate appropriate graphs for exploratory analysis.
8. Record and interpret important observations from the analysis.

## Statistical Techniques Used

### Descriptive Statistics

Descriptive statistics are used to summarize numerical variables using measures such as:

* Mean
* Median
* Minimum
* Maximum
* Variance
* Standard Deviation

### Missing Value Analysis

The dataset is checked for missing or potentially invalid values. Zero values in variables such as **Glucose, BloodPressure, SkinThickness, Insulin, and BMI** may require investigation because they may represent missing or invalid measurements.

### Outlier Analysis

Potentially unusual observations are identified using statistical summaries and visualizations such as boxplots. These observations are investigated before deciding whether they should be removed or retained.

### Data Visualization

Visualizations are used to understand:

* Variable distributions
* Diabetes outcome frequency
* Relationships between variables
* Potential outliers

The experiment uses visualizations such as histograms, boxplots, bar charts, and scatter plots.

## Important Observations

The exploratory analysis showed that **Glucose** has a strong association with the Outcome variable. BMI and Age also show noticeable relationships with the Outcome. Potentially invalid zero values and extreme Insulin values require attention before further analysis or model development.

## Results

The experiment successfully:

* Inspected the structure of the dataset.
* Performed descriptive statistical analysis.
* Identified potentially invalid values.
* Identified potential outliers.
* Generated statistical visualizations.
* Observed important relationships between variables.
* Interpreted the findings from the exploratory analysis.

## Conclusion

Exploratory statistical analysis was successfully performed on the Pima Indians Diabetes Dataset. The analysis helped understand the dataset structure, variable characteristics, data quality, distributions, outliers, and important patterns. This exploratory analysis provides a foundation for further statistical analysis and machine learning model development.

---

# Screenshots

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0372f993-61f5-4eac-a4d7-2d2a01b08882" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a15fd55f-986d-4976-a4c2-847ca6029f6b" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/abf7afcd-7b34-4101-841d-7ee019ad3141" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8685b2e1-4820-4554-a514-30394676966c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/27f99402-8578-45cc-b141-128d07c2b3e6" />

