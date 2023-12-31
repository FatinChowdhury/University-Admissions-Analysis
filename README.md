# University Admissions Analysis
Project by Fatin Chowdhury and Karim Mawji

# Project Overview:

This project addresses the complexity of university admissions by utilizing data-driven techniques.
It employs linear regression to establish correlations and predict admission likelihood based on various application metrics.
The dataset used is the "Graduate Admissions" dataset from Kaggle, encompassing GRE scores, TOEFL scores, university ratings, SOP/LOR strength, CGPA, and research experience.
The goal is to create a predictive model that estimates admission chances.
Linear regression is the primary tool chosen for its interpretability and suitability for the target variable, admission likelihood.

# Model and Numerical Methods:
This project's core is a linear regression model that predicts university admission chances based on multiple application factors,
including GRE and TOEFL scores, University Rating, SOP/LOR strength, CGPA, and Research Experience.
The Ordinary Least Squares method is employed to find the best-fit line by minimizing the differences between observed and predicted values.

Python and its libraries, including Pandas for data manipulation, NumPy for mathematical computations,
Matplotlib for data visualization, and Scikit-Learn for implementing linear regression, are used.

The project follows these key steps:

Data loading and preliminary integrity checks.
Data splitting into training (80%) and test (20%) sets.
Model training using Scikit-Learn's LinearRegression class.
Predicting admission chances on the test data.
Model evaluation using metrics like R-squared, Mean Absolute Error, Mean Squared Error, and Root Mean Squared Error.


# Testing and Validation:
In the testing and validation phase, several crucial steps were taken to ensure the reliability and accuracy of the model:

Data Consistency: The dataset was thoroughly inspected to ensure data integrity.
This involved checking for missing values and gaining insights into the distribution of each variable.

Data Split: The dataset was correctly divided into two subsets - a training set and a test set.
This separation was essential for verifying the model's performance.

Model Coefficients: The model's coefficients and intercept were scrutinized to confirm their practicality and relevance within the context of the data.
This step helped ensure that the model's output made sense.

Model Validation: The test set was utilized to validate the model's functionality and accuracy.
It served as an independent dataset to assess how well the model generalized to unseen data.

Overall, this phase focused on rigorous testing and validation to guarantee the model's robustness
and its ability to provide accurate predictions beyond the training data.


# Key Findings:
The linear regression model provided valuable insights into university admissions:

The model captured a significant portion of admission chance variations (R-squared).
CGPA and GRE scores were the most influential factors, positively affecting admission chances.

Visualizations, including a bar chart of admission by university rating and scatter plots with lines of best fit,
highlighted these influences and other subtle associations.

The project's findings offer valuable guidance to prospective students by revealing the factors that impact admission prospects.

# Results and Discussion:

The model's evaluation metrics include R-squared (81.88%), MAE (0.0427), MSE (0.0037), and RMSE (0.0609), indicating good prediction accuracy.
Visualizations showed higher scores, more letters of recommendation, and lower university ratings correlated with higher admission chances.
CGPA and GRE scores are key factors affecting acceptance rates.
Limitations include a small dataset and exclusion of other admission factors like interviews and essays.
Future improvements may involve a more comprehensive dataset and advanced modeling techniques like decision trees for increased accuracy.

# Conclusion:

Our model emphasized the significance of high CGPA and GRE scores in graduate admissions, highlighting the importance of academic excellence.
However, it had limitations due to a small dataset and the exclusion of key factors like interviews and essays.
Future improvements involve gathering a more diverse dataset and exploring advanced modeling techniques like decision trees
to better understand complex admissions processes.
