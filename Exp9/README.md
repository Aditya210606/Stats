Experiment 09 – Machine Learning Model Evaluation and Explainability
Title - Evaluate and Interpret Machine Learning Models using Validation and Explainability Technique

Aim - To apply model evaluation, Bayesian inference concepts, and explainable AI techniques to interpret and understand machine learning predictions on the Pima Indians Diabetes Dataset.

Objectives - After completing this experiment, the following objectives were achieved:

Applied model evaluation and Bayesian concepts to analyze the reliability of machine learning predictions.
Applied Explainable AI techniques to interpret model predictions.
Identified important features influencing the model's predictions.
Evaluated the model using k-fold cross-validation.
Analyzed the reliability of predicted probabilities using calibration analysis and Brier Score.
Used SHAP to explain individual and overall model predictions.
Tools and Technologies Used
Python 3.x
Google Colab / Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-learn
SHAP
LIME
Dataset

Dataset: Pima Indians Diabetes Dataset

The dataset contains diagnostic information for 768 female patients.

The target variable is:

Outcome = 0 → Non-diabetic
Outcome = 1 → Diabetic
Methodology

The experiment follows the workflow:

Dataset
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Model Training
   ↓
K-Fold Cross-Validation
   ↓
Performance Evaluation
   ↓
Calibration Analysis
   ↓
Brier Score
   ↓
Explainable AI
   ↓
SHAP / LIME
   ↓
Feature Importance
   ↓
Interpretation
Procedure
Load and preprocess the Pima Indians Diabetes Dataset.
Divide the dataset into training and testing sets.
Train a Logistic Regression classification model.
Evaluate the model using 5-fold cross-validation.
Calculate performance measures such as Accuracy and F1-Score.
Calculate the Brier Score.
Generate a calibration curve to analyze probability reliability.
Apply SHAP to explain model predictions.
Identify the important features influencing the predictions.
Interpret and document the model evaluation and explainability results.
Model Used
Logistic Regression

Logistic Regression was used as the classification model to predict whether a patient is diabetic or non-diabetic.

The model was implemented using a Scikit-learn pipeline with:

StandardScaler
LogisticRegression
Model Evaluation

The model was evaluated using:

Accuracy

Accuracy measures the proportion of correctly classified observations.

F1-Score

F1-Score combines Precision and Recall and provides a balanced measure of classification performance.

K-Fold Cross-Validation

In k-fold cross-validation, the dataset is divided into k subsets. The model is trained on k-1 subsets and tested on the remaining subset.

This process is repeated k times, and the final performance is calculated using the average performance across all folds.

For this experiment, 5-fold cross-validation was used.

Calibration Analysis

A calibration curve compares:

Predicted Probability
Observed Frequency

A well-calibrated model produces predicted probabilities that are reasonably close to the actual observed frequency.

The experiment generated a calibration curve for the Logistic Regression model.

Brier Score

The Brier Score measures the accuracy of probabilistic predictions.

The formula is:

BS = (1/N) Σ(pᵢ - yᵢ)²

where:

pᵢ = predicted probability
yᵢ = actual outcome

A lower Brier Score generally indicates better probabilistic predictions.

Explainable AI

Explainable AI techniques were used to understand why the model produced particular predictions.

SHAP

SHAP (SHapley Additive exPlanations) values explain the contribution of individual features to a model prediction.

SHAP helps identify:

Which features increase the predicted probability.
Which features decrease the predicted probability.
Which features have the greatest influence on the model.
LIME

LIME explains an individual prediction by creating small variations around an observation and approximating the model locally using an interpretable model.

Important Features

Based on the SHAP analysis, the important features influencing the model predictions included:

Glucose
BMI
Pregnancies
DiabetesPedigreeFunction
Age
Insulin
BloodPressure
SkinThickness

The SHAP visualizations in the experiment show the relative contribution and importance of these features.

Results

The experiment successfully:

Trained a Logistic Regression classification model.
Evaluated the model using 5-fold cross-validation.
Calculated Accuracy and F1-Score.
Calculated the Brier Score.
Generated a calibration curve.
Applied SHAP for model explainability.
Identified important features affecting predictions.
Explained an individual prediction using SHAP.
Conclusion

The classification model was evaluated using cross-validation and calibration analysis to understand its performance and reliability. Explainable AI techniques such as SHAP were applied to identify the features influencing individual predictions. The experiment demonstrated that model performance, probability reliability, and interpretability are important aspects of evaluating machine learning systems.

Screenshots :

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/898c498d-aa1a-48da-bb65-64a261d68fb4" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d4491bdf-7e1c-415d-a4e1-81070ecf2f57" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42505f66-9c58-45d8-b0f4-81282a8a3061" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c378d52a-3b68-4a4f-8549-016a67721300" />


