
# Telecom Churn Prediction

The Telecom Churn Prediction project aims to identify customers who are likely to leave a telecommunications service provider. By leveraging decision trees and random forest algorithms, this project analyzes customer data to predict churn, enabling the company to implement targeted retention strategies.


## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- seaborn
- Statsmodels

## Modeling Techniques

- Logistic Regression

      1. Implemented a logistic regression model to estimate the probability of customer churn.
     
      2. Analyzed coefficients to understand the impact of different features on the likelihood of churn.

      3. Utilized the logistic function to map predicted values to probabilities, facilitating interpretation.

- Recursive Feature Elimination (RFE)
      
      1. Employed RFE to select the most significant features for predicting churn.
      
      2.Enhanced model interpretability and performance by reducing dimensionality and focusing on relevant predictors.

## Data Preprocessing

- Data Cleaning: Handled missing values and irrelevant features.
- Feature Engineering: Created new features to enhance model performance.
- Data Encoding: Converted categorical variables into numerical formats.
- Train-Test Split: Divided the data into training and testing sets for model evaluation
## Evaluation Metrics

- Sensitivity
  
  Sensitivity (True Positive Rate) measures the proportion of actual positives that are correctly identified. It is critical in churn prediction to minimize false negatives (i.e., retaining customers who are likely to leave).

- Specificity

  Specificity (True Negative Rate) measures the proportion of actual negatives that are correctly identified. This metric helps understand the model's ability to correctly identify retained customers, minimizing false positives.

## Results

- Provided metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.

- Presented confusion matrices and ROC curves to visualize model effectiveness.
