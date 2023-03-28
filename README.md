# Factors contributing to customer churning.
This project focuses on classification and predictive modeling on the Bank Customer Churn Prediction dataset. The dataset contains customer information such as age, gender, credit score, country, balance, number of products used, and whether the customer churned or not.

## Installation
Python 3.x must be installed on your system.
Required packages: pandas, numpy, seaborn, matplotlib, scikit-learn.
## Usage
Download the dataset "Bank Customer Churn Prediction.csv" from the source.
Open the Jupyter Notebook file "classification-and-predictive-modelling.ipynb" in Jupyter Notebook or Google Colab.
Run the code cells to perform exploratory data analysis, data preprocessing, feature selection, and modeling.
The dataset is preprocessed by dropping the 'customer_id' column and performing one-hot encoding on the categorical variables 'country' and 'gender'.
The data is split into training and testing sets with a 80-20 ratio using the train_test_split function.
Two classification models are developed:
Random Forest Classifier
Decision Tree Classifier
The models are evaluated using the accuracy score, confusion matrix, and classification report.
## Exploratory Data Analysis
The dataset has 10,000 rows and 14 columns.
The 'age' variable shows the strongest correlation with churn than the other variables.
The scatterplot between the estimated salary and age does not give quite clear conclusions.
The countries represented in the dataset are visualized using a bar chart.
## Model Development
Two models are developed: Random Forest Classifier and Decision Tree Classifier.
Random Forest Classifier is used to build a predictive model. The accuracy score achieved is 85.5%.
Decision Tree Classifier is used to build a predictive model with a maximum depth of 6. The accuracy score achieved is the same as the Random Forest algorithm.
## Future Improvements
Further feature engineering may be required to improve the accuracy of the models.
Other classification algorithms like Logistic Regression, Support Vector Machines, and Naive Bayes could be explored for better model performance.
Cross-validation and hyperparameter tuning can also be performed for better model optimization.
### Author
This project was written by [Caroline Lankenua].






