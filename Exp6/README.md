# Experiment 06 – Regression Model Development and Evaluation

## Title - **Develop and Evaluate Regression Models using Statistical Performance Measures**

## Aim - To develop a regression model for predicting a continuous variable using the **Pima Indians Diabetes Dataset** and evaluate its performance using suitable statistical measures.

## Objectives - After completing this experiment, the following objectives were achieved:

1. Developed a regression model using medical attributes.
2. Preprocessed the dataset and selected suitable features.
3. Predicted a continuous target variable.
4. Evaluated the regression model using statistical performance measures.
5. Compared actual and predicted values.
6. Analyzed prediction errors using residual analysis.

## Tools and Technologies Used

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Dataset

**Dataset:** Pima Indians Diabetes Dataset

The dataset contains medical information for **768 female patients**.

For this experiment, **BMI** is used as the continuous target variable, while other medical attributes are used as input features.

## Methodology

The experiment follows the workflow:

```text
Dataset
   ↓
Data Preprocessing
   ↓
Feature and Target Selection
   ↓
Train-Test Split
   ↓
Regression Model
   ↓
Prediction
   ↓
Performance Evaluation
   ↓
Residual Analysis
   ↓
Interpretation
```

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select BMI as the target variable and relevant attributes as input features.
3. Handle invalid or missing values.
4. Divide the dataset into training and testing sets.
5. Develop and train a regression model.
6. Generate predictions for the test data.
7. Compare actual and predicted values.
8. Calculate regression performance measures.
9. Analyze the residuals of the model.
10. Interpret the obtained results.

## Model Used

### Linear Regression

Linear Regression was used to predict the continuous BMI value from the selected medical attributes.

The model establishes a relationship between the dependent variable and one or more independent variables.

The multiple linear regression equation is:

```text
y = β₀ + β₁x₁ + β₂x₂ + ... + βₚxₚ + ε
```

where `y` represents the target variable, `x` represents the predictor variables, `β` represents model coefficients, and `ε` represents the error term.

## Model Evaluation

The regression model was evaluated using the following measures:

### Mean Absolute Error (MAE)

MAE represents the average absolute difference between the actual and predicted values.

### Mean Squared Error (MSE)

MSE calculates the average squared prediction error. Larger errors receive greater importance because the errors are squared.

### Root Mean Squared Error (RMSE)

RMSE is the square root of MSE and represents the prediction error in the same units as the target variable.

### R² Score

R² indicates the proportion of variation in the target variable that is explained by the regression model.

## Residual Analysis

A residual is the difference between the actual and predicted value:

```text
Residual = Actual Value − Predicted Value
```

Residual analysis helps identify prediction errors, unusual observations, and possible patterns that may indicate limitations in the regression model.

A residual plot can be used to visualize the distribution of prediction errors.

## Results

The experiment successfully:

* Developed a Linear Regression model.
* Predicted BMI values using medical attributes.
* Compared actual and predicted BMI values.
* Calculated MAE, MSE, RMSE and R² Score.
* Visualized the relationship between actual and predicted values.
* Performed residual analysis.
* Interpreted the performance of the regression model.

## Conclusion

A regression model was developed using the Pima Indians Diabetes Dataset to predict a continuous health-related variable. The model was evaluated using statistical performance measures such as MAE, MSE, RMSE and R² Score. Residual analysis was also performed to understand the prediction errors and limitations of the model.

---

# Screenshots:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aa072409-9d48-4c94-a0b3-15eab19b91ee" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/452a4e4e-b778-4b1c-8bd1-05b5682e2ccc" />

