# Loan Default Prediction
### Problem statement:
The primary objective of this project is to help financial institutions reduce loan default risk before approving a loan for a potential customer, the institution can assess the customer’s likelihood of loan default, and if the risk is found to be significantly high, the loan application can be rejected or reviewed more carefully.. By identifying applicants with a high probability of default in advance, banks can minimize non-performing assets (NPAs) and improve overall operational efficiency.

### Method:
Executing machine learning tasks such as Data Exploration, Data Cleaning, Feature Engineering, Model Building, and Model Testing to construct a solution capable of predicting loan repayment risk before approving for the loan.

Here's how each step was carried out:

####step 1:
Data Exploration: Investigated the dataset using libraries like pandas, numpy, matplotlib and seaborn.

Exploratory Data Analysis: Generated various graphs to gain deeper insights into both dependent and independent variables.

####step 2:
Feature Engineering: Rescaled numerical variable to calculate new features and encoded categorical ones.

####step 3:
Model Building: Started with dataset splitting, then proceeded to train Machine Learning Algorithm, Logistic Regression.

####step 4:
Model Selection: Evaluated the model based on p-value and log-likelihood.

### Conclusion

In this project, a logistic regression model was developed to predict loan repayment behavior using customer and loan-related features. The model was trained on 19,076 observations and successfully converged, indicating a stable and reliable estimation process.

The model achieved a Pseudo R² of 0.331, suggesting that it explains a substantial portion of the variation in loan repayment outcomes. The highly significant Likelihood Ratio test (LLR p-value < 0.001) confirms that the model is statistically significant.

Additionally, the model achieved an accuracy score of 85.51%, demonstrating strong overall predictive performance.

Overall, this model can serve as a valuable decision-support tool for financial institutions by enabling data-driven loan approval decisions, reducing non-performing assets, and improving credit risk management efficiency. Further improvements may include  large sample and exploring other machine learning models to enhance predictive accuracy.

### Libraries used:
1) Pandas
2) Numpy
3) Matplotlib
4) Seaborn
5) Scikit-Learn
6) Statsmodels
   
### Tools used:
1) Jupyter Notebook
2) MySQL
3) Excel
