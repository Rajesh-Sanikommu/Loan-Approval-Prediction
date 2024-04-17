# Loan Approval Prediction with Machine Learning

## Overview
Loan Approval Prediction is a crucial task in the financial industry, where businesses aim to determine whether to approve or reject loan applications based on various factors such as the applicant's financial history, income, credit rating, employment status, and other relevant attributes. This project demonstrates how Machine Learning techniques can be utilized to build an intelligent system for loan approval prediction using Python.

## Dataset
The dataset used for this project contains information about loan applicants, including features such as gender, marital status, education, income, loan amount, loan term, credit history, property area, and loan status. The dataset is available in CSV format and can be downloaded from Kaggle.
## Steps Followed
1. **Importing Necessary Libraries and Dataset**:
   - Imported required Python libraries such as pandas, numpy, scikit-learn, and plotly.

2. **Data Preprocessing**:
   - Dropped unnecessary columns like 'Loan_ID'.
   - Checked for missing values and filled them appropriately.
   
3. **Exploratory Data Analysis (EDA)**:
   - Visualized the distribution of various features and explored relationships with the target variable ('Loan_Status').

4. **Data Preparation**:
   - Converted categorical columns into numerical ones using one-hot encoding.
   - Split the dataset into training and testing sets.
   - Scaled the numerical features using StandardScaler.

5. **Model Training**:
   - Selected a Support Vector Machine (SVM) classifier for loan approval prediction.
   - Trained the model on the training data.

6. **Model Evaluation**:
   - Made predictions on the test set and evaluated the model's performance using accuracy and other relevant metrics.

7. **Summary and Conclusion**:
   - Summarized the project, including the problem statement, dataset used, steps followed, and results obtained.
   - Discussed the significance of loan approval prediction in the financial industry.
   - Encouraged further exploration and experimentation with different algorithms and techniques.


## Results
The trained model achieved:  
**Accuracy**: 83% (The percentage of correctly predicted loan approvals out of all predictions)  
**Precision**: 80% (The ratio of correctly predicted positive outcomes (loan approvals) to the total predicted positive outcomes)  
**Recall**: 99% (The ratio of correctly predicted positive outcomes to the total actual positive outcomes)   
**F1-score**: 89% (The harmonic mean of precision and recall, providing a balance between the two metrics)   

These metrics indicate that the model performs well overall, with high accuracy and precision. The high recall suggests that the model effectively identifies a large portion of actual loan approvals. The F1-score, which balances precision and recall, is also quite high, indicating a good overall performance of the model in predicting loan approvals.


