## Loan Prediction
This project is designed to Loan Prediction using Machine Learning techniques. The Loan Prediction is a data science project aimed at utilizing advanced data analytics and machine learning techniques to enhance the accuracy of predicting Loan Prediction premiums for individuals. 

## Introduction About Project
The "Loan Prediction" is a data science project aimed at utilizing advanced data analytics and machine learning techniques to enhance the accuracy of predicting Loan Prediction premiums for individuals. 
Loan prediction, also known as credit scoring or credit risk assessment, is a critical task in the financial industry. It involves evaluating the creditworthiness of individuals or businesses applying for loans. The primary goal of loan prediction is to determine whether a borrower is likely to repay a loan or is at risk of defaulting on their financial obligations. This assessment is essential for financial institutions, such as banks, credit unions, and online lenders, to make informed lending decisions and manage risk effectively.

## Tools and Libraries
## Tools
•	Python
•	Jupyter Notebook
•	Flask
•	HTML
•	CSS
•	JavaScript
•	Heroku
•	GitHub
## Libraries
•	Pandas
•	Scikit-Learn
•	Numpy
•	Seaborn
•	Matplotlib
## Data Collection
For this project, we utilized data available on Kaggle. The dataset contains 7 columns and 614 rows, featuring key information about the properties ,

Project Flow
## Exploratory Data Analysis (EDA)
## Data Cleaning
We started with 7 columns but removed unnecessary Data cleaning included:
•	Gender	
•	Married
•	Dependents
•	Education
•	Self_Employed
•	Credit_History
•	Property_Area

•	Handling missing values
•	Removing corrupted data
•	Date and text parsing
## EDA
Exploratory Data Analysis (EDA) is a critical initial step in the data analysis process. It involves investigating, summarizing, and visualizing the main characteristics of a dataset. EDA helps you understand your data, identify patterns, relationships, anomalies, and insights, which are crucial for making informed decisions and formulating hypotheses for more advanced analyses.
## Data Collection and Inspection:
Gather the dataset you intend to analyse.	
Inspect the data to ensure it's in a usable format.
Check for missing values, duplicates, and outliers
## Feature Engineering
We discovered outliers in a bmi column applied the IQR method for outlier removal. 
We have replaced outliers with upper_tail , now dataset having no outlier checked from using seaborn library.
## Data Normalization
We used min-max normalization to scale numerical features between 0 and 1.
## Model Deployment
The model was integrated into a user-friendly web interface using HTML, CSS, and Flask.
## Model Conclusion
The model predicts housing prices with 85% accuracy on test data.
## Project Innovation
•	User-friendly
•	Open source
•	High accuracy
•	GUI-based application
## Limitations and Next Steps
## Limitations:
•	Lack of a mobile application
•	Potential for further accuracy improvements
•	Large model size (~310MB)
•	Limited feature set
## Next Steps:
•	Develop a mobile application
•	Reduce model size using Principal Component Analysis (PCA)


