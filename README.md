# Employee Attrition Analysis

This project aims to analyze employee attrition using the IBM HR dataset. The goal is to gain insights into why employees are leaving and identify potential indicators of attrition. The project also explores a hypothesis that suggests employees with higher job satisfaction and higher salaries are less likely to leave the company. The findings can be applied to help companies adjust their work conditions.

## Milestone 1

### Data Preparation and Exploration

- Loaded the IBM HR dataset from Kaggle.
- Removed unnecessary columns: 'EmployeeCount', 'Over18', 'StandardHours'.
- Removed duplicate entries.
- Imputed missing values in 'Age' with the median.
- Dropped 'EmployeeNumber' column.
- Converted 'Education' to a categorical variable.
- Renamed columns for clarity.
- Removed highly correlated features.
- Plotted histograms for numerical variables to visualize data distribution.
- Plotted bar charts for categorical variables to explore categorical data trends.
- Applied a log transformation to 'MonthlyIncome' for better visualization.

### Data Splitting

- Split the data into training and testing sets (80% training, 20% testing).
- Saved the data splits as CSV files: 'train_data.csv' and 'test_data.csv'.
- Printed the shapes of the data splits.

## Milestone 2

### Data Refinement

- Removed 'DistanceFromHome' and 'TotalWorkingYears' columns as they were deemed less impactful.
- Plotted histograms for numerical variables after removing the columns.

## Milestone 3

### Model Selection and Evaluation

- Chose a Logistic Regression model for its interpretability and suitability for binary classification tasks.
- Trained the model on the training dataset.
- Made predictions on the testing dataset.
- Evaluated the model using metrics including Accuracy, Precision, Recall, F1-score, and ROC-AUC.

### Model Evaluation Results

- Accuracy: 86%
- ROC-AUC: 0.5

## Conclusion

While the model achieved decent accuracy, it struggles with other evaluation metrics, especially ROC-AUC. Further analysis and refinement of the model and features may be necessary to improve its predictive power.

Feel free to explore the code and data files to gain more insights into the analysis and model used in this project.

For questions or additional information, contact Zach at zach.campb3ll@gmail.com.
