# Employee-Attrition
Analyzed a dataset of 1,000,000 employee records, identifying key factors influencing attrition and developing predictive models with an RMSE of approximately 19.07 using optimized LightGBM.

This project involves a comprehensive analysis of employee attrition using a large dataset of 1,000,000 employee records. The goal is to identify key factors influencing employee turnover and develop predictive models to forecast attrition.

Key Features of the Dataset
Size: The dataset consists of 1,000,000 samples.

Features:

Categorical Variables: Job type, degree, major, industry.

Numerical Variables: Years of experience, distance from the metropolis, salary.

Methodology
Data Preprocessing:

Handling Missing Values: No missing values were found in the dataset.

Scaling: Numerical features were scaled using Min-Max Scaler.

Encoding: Categorical variables were encoded using One-Hot Encoding.

Exploratory Data Analysis (EDA):

Correlation Analysis: Identified positive correlation between years of experience and salary, and a weak negative correlation between distance from the metropolis and salary.

Chi-Square Tests: Revealed significant relationships between job type and degree, job type and major, and degree and major.

ANOVA Tests: Showed significant differences in salary means across different majors, job types, degrees, and industries.

Modeling:

Models Compared: Linear Regression, Random Forest, Gradient Boosting, Decision Tree, AdaBoost, XGBoost, and LightGBM.

Hyperparameter Tuning: RandomizedSearchCV was used to optimize hyperparameters for each model.

Best Performer: LightGBM achieved the best performance with an RMSE of approximately 19.07 on the test set.

Business Insights:

Salary Discrepancies: Predicted salaries for a sample of low-paid employees often exceeded actual salaries, indicating potential underpayment issues.

Conclusion
This project demonstrates the application of machine learning techniques to analyze employee attrition. By identifying key factors and optimizing predictive models, organizations can better understand and address issues contributing to turnover.
