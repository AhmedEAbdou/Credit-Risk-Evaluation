# Credit-Risk-Evaluation-Using-Machine-Learning

Title: German Credit Risk Prediction

Objective:

The objective of this project was to predict the credit risk of applicants based on their personal and financial information. By leveraging machine learning techniques, we aimed to develop a model that could help in making better credit decisions, ultimately maximizing net profit.

Dataset: The dataset used in this project is the German Credit dataset, which consists of 1,000 records and 30 predictor variables. Each applicant was rated as either "good credit" (700 cases) or "bad credit" (300 cases). The dataset also includes an opportunity cost table that quantifies the costs of misclassification.

Methods: The dataset was first divided into training and validation partitions. Then, various classification models were developed using R, specifically logistic regression, classification trees, and neural networks. The performance of these models was evaluated based on confusion matrices, cost/gain matrices, and net profit.

​

Summary of the project steps:

Data Exploration: The predictor variables were reviewed to understand their potential role in credit decisions. A thorough analysis was conducted to identify any surprises or irregularities in the data.

Data Preprocessing: The dataset was divided into training and validation partitions to ensure proper model evaluation.

Model Development: Three classification models were developed using R, including logistic regression, classification trees, and neural networks.

Model Evaluation: The confusion matrix and cost/gain matrix for each model were reported for the validation data to identify the technique with the highest net profit.

Model Improvement: To further enhance the performance, the estimated probabilities (propensities) from the logistic regression were used as a basis for selecting the best credit risks first, followed by poorer-risk applicants. A decile-wise lift chart incorporating net profit was created for the validation set.

Results Analysis: Based on the lift chart, the optimal point in the validation data was identified to achieve maximum net profit. Additionally, the "probability of success" cutoff for extending credit was determined for future applicants using the logistic regression model.

​​

Conclusion:

This project successfully demonstrated the use of machine learning techniques to predict credit risk and make better credit decisions. The developed models can be utilized by financial institutions to improve their credit approval process and maximize net profit. The detailed analysis and results can be showcased in a portfolio website to demonstrate the problem-solving skills and expertise of the candidate to potential recruiters.
