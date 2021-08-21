# Supervised Machine Learning and Credit Risk

## Overview
The purpose of this project was to build and evaluate several machine learning models and algorithms. These models were compared against each other to assess which model best predicts those clients with low or high credit risk. We used "imbalanced-learn" and "scikit-learn" libraries to create the following machine learning models:
- Logistic regression with naive random oversampling and SMOTE oversampling algorithms
- Logistic regression with Cluster Centroids undersampling algorithm
- Logistic regression with SMOTEENN combined over- and under-sampling algorithm
- Balanced Random Forest Classifier versus Easy Ensemble Classifier algorithms

## Results
### Logistic Regression: Naive Random Oversampling
- Balanced accuracy score: 0.66
- Precision scores
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores
  - High risk: 0.70
  - Low risk: 0.63

![Image of balanced accuracy score](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/Naive%20ROS%20Balanced%20Accuracy%20Score.png)
![Image of confusion matrix](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/Naive%20ROS%20Confusion%20Matrix.png)
![Image of classification report](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/Naive%20ROS%20Classification%20Report.png)

### Logistic Regression: SMOTE Oversampling
- Balanced accuracy score: 0.66
- Precision scores
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores
  - High risk: 0.63
  - Low risk: 0.69

![Image of balanced accuracy score](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE%20Balanced%20Accuracy%20Score.png)
![Image of confusion matrix](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE%20Confusion%20Matrix.png)
![Image of classification report](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTE%20Classification%20Report.png)

### Logistic Regression: Cluster Centroids Undersampling
- Balanced accuracy score: 0.54
- Precision scores
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores
  - High risk: 0.69
  - Low risk: 0.39

![Image of balanced accuracy score](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/ClusterCentroids%20Balanced%20Accuracy%20Score.png)
![Image of confusion matrix](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/ClusterCentroids%20Confusion%20Matrix.png)
![Image of classification report](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/ClusterCentroids%20Classification%20Report.png)

### Logistic Regression: SMOTEENN Combination Over- and Under-sampling
- Balanced accuracy score: 0.68
- Precision scores
  - High risk: 0.01
  - Low risk: 1.00
- Recall scores
  - High risk: 0.77
  - Low risk: 0.58

![Image of balanced accuracy score](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEENN%20Balanced%20Accuracy%20Score.png)
![Image of confusion matrix](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEENN%20Confusion%20Matrix.png)
![Image of classification report](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/SMOTEENN%20Classification%20Report.png)

### Ensemble Learner: Balanced Random Forest Classifier
- Balanced accuracy score: 0.79
- Precision scores
  - High risk: 0.03
  - Low risk: 1.00
- Recall scores
  - High risk: 0.70
  - Low risk: 0.87

![Image of balanced accuracy score](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/RandomForestClassifier%20Balanced%20Accuracy%20Score.png)
![Image of confusion matrix](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/RandomForestClassifier%20Confusion%20Matrix.png)
![Image of classification report](https://github.com/jpb12002/Credit_Risk_Analysis/blob/main/Resources/Images/RandomForestClassifier%20Classification%20Report.png)
