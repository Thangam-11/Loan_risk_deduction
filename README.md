# Financial Loan Risk Default Prediction:

Introduction:

This project addresses the challenges faced by lending institutions in assessing creditworthiness and predicting loan defaults. Leveraging machine learning techniques, the goal is to develop models that accurately predict the likelihood of a borrower defaulting on a loan. These models can assist lending institutions in making informed decisions about loan approvals, thus reducing the risk of financial losses due to defaults.

# Table of Contents:

* Key Technologies and Skills
* Installation
* Usage
* Features
* Contributing
* License
* Contact

# Key Technologies and Skills:

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Pickle

# Installation:

To run this project, install the required packages using the following commands:

pip install numpy

pip install pandas

pip install scikit-learn

pip install xgboost

pip install matplotlib

pip install seaborn

# Usage:

To use this project, follow these steps:

Clone the repository: git clone https://github.com/Thangam-11/Loan_risk_deduction.git

Install the required packages: pip install -r requirements.txt

# Features:

* Data Preprocessing:

* Data Understanding: The dataset provides a comprehensive overview of financial loan applications, with each represented by a unique identification number. The 
  primary target variable, TARGET, indicates whether the applicant defaulted on the loan (1) or not (0), crucial for assessing credit risk. Several key features aid 
  in assessing creditworthiness, including personal demographics, financial status, employment details, housing situation, educational background, and family status. 
  These attributes provide valuable context for evaluating an applicant's financial stability and ability to repay a loan.

* Handling Null Values:High percentages of null values may indicate data quality issues or inconsistencies. Dropping such columns can help maintain data integrity.
  categorical null values were handled, such as using a separate category label or imputing with Unknown.Numerical null values were handled, such as using a separate   imputing with Mean values.
  
* Encoding and Data Type Conversion:* The process involves preparing categorical features for modeling by transforming them into numerical representations, 
  considering their inherent nature and relationship with the target variable
  
# Feature Selection Using PCA: Enhancing Model Efficiency:

   PCA, is a dimensionality reduction technique employed to transform a dataset with numerous correlated features into a set of linearly uncorrelated variables known 
   as principal components.PCA allows us to condense the dataset's complexity while retaining the essential information that contributes most significantly to 
   variance.
  
  *  Handling Data Imbalance: In our predictive analysis, we encountered data imbalance within the 'Target' feature. To address this issue, we implemented the 
     SMOTETomek oversampling method, ensuring our dataset is well-balanced. This enhancement significantly enhances the performance and reliability of our 
     classification tasks, yielding more accurate results in distinguishing between success and failure.
    
 # Machine Learning Classfication Model:

   Model-Building:The first step in our algorithmic odyssey involves the division of the dataset into training and testing subsets. This partitioning ensures a 
   robustevaluation of algorithmic performance, with the training set serving as the crucible for model learning and the testing set acting as a litmus test for 
   predictive accuracy on unseen data.

* Algorithm Selection: After thorough evaluation Logistic Regression and XGB Classfication both are good testing accuracy.I choose the Xgb classfication for its 
   ability to strike a balance between interpretability and accuracy, ensuring robust performance on unseen data.
  
* Hyperparameter Tuning with GridSearchCV and Cross-Validation: To fine-tune our model and mitigate overfitting, we employ GridSearchCV with cross-validation for 
  hyperparameter tuning. This function allows us to systematically explore multiple parameter values and return the optimal set of parameters.
 { n_estimators=150,learning_rate=0.2,'max_depth': 7, }

* Model Accuracy and Metrics: With the optimized parameters, our XGB Classifier achieves an impressive 73% accuracy, ensuring robust predictions for 
 unseen data. To further evaluate our model, we leverage key metrics such as the confusion matrix, precision, recall, F1-score, AUC, and ROC curve, providing a comprehensive view of its performance.

# Contributing:
Contributions to this project are welcome! If you encounter issues or have suggestions for improvements, please submit a pull request.

# License:
This project is licensed under the MIT License. Refer to the LICENSE file for more details.

# Contact:

Email: thangamani1128@gmail.com

LinkedIn: linkedin.com/in/thangarasu-m-

For any further questions or inquiries, feel free to reach out. We are happy to assist you with any queries.





