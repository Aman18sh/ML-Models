**Car Dataset Multi Linear Regression**

**Overview**

In this project, I have implemented Multi Linear Regression on a car dataset that consists of both numerical and categorical columns. The primary objective is to predict the horsepower of cars based on various features.

**Dataset Description**

The car dataset contains 5076 rows and:

Numerical Columns: 9

Categorical Columns: 8

Among the numerical columns, 8 are used as features for prediction, and 1 column represents the target variable, which is the horsepower of the car.

**Methodology**

Exploratory Data Analysis (EDA)

Data Inspection:

Analyzed the structure of the dataset to understand the distribution of numerical features and the categories within categorical features.

Outlier Detection:

Identified hidden outliers that negatively impacted the predictive accuracy of the model.

Data Preprocessing

Outlier Removal:

Removed outliers from the dataset to improve model performance.

Feature Scaling:

Performed scaling on the remaining data to ensure that all numerical features contribute equally to the model training process.

**Model Implementation**

Implemented Multi Linear Regression using the cleaned and scaled numerical columns.

The model was trained using 8 features to predict horsepower.

**Findings**

The removal of outliers significantly improved the predictive accuracy of the Multi Linear Regression model.

Scaling of data post-outlier removal further enhanced model performance.

**Results**

The final model was evaluated based on its predictive accuracy, and it demonstrated a substantial improvement after preprocessing steps were applied.

**Conclusion**

This project highlights the importance of data cleaning and preprocessing in building effective predictive models. By addressing outliers and scaling numerical features, we can achieve better performance in Multi Linear Regression tasks.

