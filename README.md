# Diabetes Prediction Project

This project focuses on predicting the onset of diabetes based on various medical predictor variables using machine learning classification models. The dataset consists of several medical attributes such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age, with the target variable "Outcome" indicating the presence or absence of diabetes.

## Dataset Description
- **Pregnancies**: Number of times pregnant.
- **Glucose**: Plasma glucose concentration 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skin fold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: Diabetes pedigree function.
- **Age**: Age in years.
- **Outcome**: Class variable (0 or 1), with 1 indicating the presence of diabetes.

## Model Evaluation Metrics
The project evaluates the performance of various classification models using precision, recall, F1-score, and support. The models compared include:
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression
- Naive Bayes
- Decision Tree
- Gradient Boosting
- XGBoost

## Results
The precision, recall, F1-score, and accuracy metrics for each model are provided below:

### Train Set Performance
- Random Forest:
  - Precision: 1.000
  - Recall: 1.000
  - F1-score: 1.000
  - Accuracy: 1.000
- KNN:
  - Precision: 0.845
  - Recall: 0.840
  - F1-score: 0.839
  - Accuracy: 0.840
- SVM:
  - Precision: 0.852
  - Recall: 0.849
  - F1-score: 0.848
  - Accuracy: 0.849
- Logistic Regression:
  - Precision: 0.747
  - Recall: 0.746
  - F1-score: 0.746
  - Accuracy: 0.746
- Naive Bayes:
  - Precision: 0.738
  - Recall: 0.737
  - F1-score: 0.737
  - Accuracy: 0.738
- Decision Tree:
  - Precision: 1.000
  - Recall: 1.000
  - F1-score: 1.000
  - Accuracy: 1.000
- Gradient Boosting:
  - Precision: 0.934
  - Recall: 0.934
  - F1-score: 0.934
  - Accuracy: 0.934
- XGBoost:
  - Precision: 1.000
  - Recall: 1.000
  - F1-score: 1.000
  - Accuracy: 1.000

### Test Set Performance
- Random Forest:
  - Precision: 0.824
  - Recall: 0.815
  - F1-score: 0.813
  - Accuracy: 0.815
- KNN:
  - Precision: 0.753
  - Recall: 0.749
  - F1-score: 0.749
  - Accuracy: 0.750
- SVM:
  - Precision: 0.798
  - Recall: 0.789
  - F1-score: 0.788
  - Accuracy: 0.790
- Logistic Regression:
  - Precision: 0.746
  - Recall: 0.745
  - F1-score: 0.744
  - Accuracy: 0.745
- Naive Bayes:
  - Precision: 0.710
  - Recall: 0.710
  - F1-score: 0.710
  - Accuracy: 0.710
- Decision Tree:
  - Precision: 0.716
  - Recall: 0.715
  - F1-score: 0.715
  - Accuracy: 0.715
- Gradient Boosting:
  - Precision: 0.798
  - Recall: 0.794
  - F1-score: 0.794
  - Accuracy: 0.795
- XGBoost:
  - Precision: 0.794
  - Recall: 0.789
  - F1-score: 0.789
  - Accuracy: 0.790

## Conclusion
The results show that the models perform well on the training set, achieving high accuracy and F1-score. However, when evaluated on the test set, the performance varies, with some models showing slightly lower scores. Overall, the Gradient Boosting and XGBoost models perform consistently well across both training and test sets, making them suitable choices for predicting diabetes onset based on the given medical attributes.
