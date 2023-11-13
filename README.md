# DIABETICS-PREDICTION-Machine-Learning-

**Abstract**

Diabetes mellitus is a chronic metabolic disorder characterized by elevated blood sugar levels (hyperglycemia). Early detection and intervention are crucial for preventing or delaying the onset of diabetes-related complications. Machine learning (ML) algorithms have emerged as promising tools for predicting diabetes risk, enabling early preventive measures. This study aims to develop and evaluate an ML-based model for predicting diabetes using a comprehensive dataset of patient-level information.

**Problem Statement**

The increasing prevalence of diabetes poses a significant global health challenge. Early identification of individuals at risk for diabetes is essential for timely intervention and improved disease management. Traditional methods for diabetes prediction, such as clinical assessments and laboratory tests, often lack specificity and may not accurately capture the complex interplay of factors contributing to the disease. ML algorithms offer the potential to analyze large datasets and identify patterns that may not be readily apparent to traditional methods, thereby improving the accuracy and effectiveness of diabetes prediction.

**Data Set**

The Pima Indian Diabetes Dataset (PIDD) from the UCI Machine Learning Repository was utilized for this study. The PIDD consists of 768 patient records, each containing 8 features:

1. Number of pregnancies
2. Plasma glucose concentration in an oral glucose tolerance test (OGTT)
3. Diastolic blood pressure (mm Hg)
4. Triceps skin fold thickness (mm)
5. 2-Hour serum insulin (mu U/ml)
6. Body mass index (BMI)
7. Diabetes pedigree function (a measure of genetic predisposition)
8. Age (years)

The target variable in the dataset indicates whether the patient has diabetes or not.

**Methodology**

A variety of ML algorithms were evaluated for diabetes prediction, including logistic regression, support vector machines (SVMs), decision trees, and random forests. The performance of each algorithm was assessed using metrics such as accuracy, precision, recall, and F1-score.

**Evaluation**

The predictive performance of the ML models was evaluated using a 10-fold cross-validation approach. The dataset was divided into 10 equal-sized folds, and each fold was used as the testing set while the remaining folds were used for training. This process was repeated 10 times, and the average performance metrics were calculated.

**Conclusion**

The results of this study demonstrate the potential of ML algorithms for predicting diabetes with high accuracy. The random forest classifier achieved the best performance, with an average accuracy of 82%. This suggests that ML-based prediction models could be valuable tools for identifying individuals at risk for diabetes, enabling early intervention and improved disease management.
