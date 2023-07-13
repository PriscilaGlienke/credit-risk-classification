Credit Risk Analysis Report

Overview of the Analysis
The purpose of this analysis was to evaluate the performance of machine learning models for predicting loan status, discriminating healthy loans from high-risk loans, using financial information data.
The variables being predicted in this analysis were binary, with 0 representing healthy loans and 1 representing high-risk loans. 
The value_counts() function as used to check the balance of our target values, to better
understand the distribution of loan statuses in the data and to observe the counts for each class.
The stages of the machine learning process used in this analysis were data preprocessing, model training, and evaluation. LogisticRegression model was also used for classification tasks, and applied resampling methods like the RandomOverSampler.

Results
Machine Learning Model 1:
* Logistic Regression Model with the Original Data:
    * Balanced Accuracy Score: Approximately 99.18%
        * Precision:
            * Healthy Loan (0): 1.00
            * High-Risk Loan (1): 0.85
        * Recall:
            * Healthy Loan (0): 0.99
            * High-Risk Loan (1): 0.91


Machine Learning Model 2:
* Logistic Regression Model with Resampled Training Data:
    * Balanced Accuracy Score: Approximately 99.38%
        * Precision:
            * Healthy Loan (0): 1.00
            * High-Risk Loan (1): 0.84
        * Recall:
            * Healthy Loan (0): 0.99
            * High-Risk Loan (1): 0.99

Summary
To summarize, based on the results, the logistic regression model with resampled training data performed better in predicting loan status in comparison to the one with original data. It’s accuracy score of 99.38% indicates an accurate classification loan status in the majority of cases. The precision and recall scores for both healthy loans and high-risk loans were also high, showing the model's ability to identify loans of different risk levels.
Therefore, the logistic regression model with resampled training data is recommended to use it for loan status prediction due to its stronger performance. This model is able to provide valuable insights to support decision-making processes, such as loan approval or risk assessment.
The performance of the models might depend on the problem to be solved. Therefore, it is very important to predict both the healthy loans and high-risk loans accurately.
