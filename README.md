# Epiliptic Seizure Prediction

This project demonstrates the classification of EEG (Electroencephalogram) data using various machine learning algorithms from scikit-learn library. The EEG data contains readings from different patients, and the goal is to classify whether a patient is epileptic or not based on the EEG readings.

## Data Preprocessing

The dataset is loaded and preprocessed as follows:

- EEG data is loaded from the provided CSV file.
- Target values are extracted and converted to binary format.
- Data is split into train, validation, and test sets.
- Imbalanced data handling using Synthetic Minority Over-sampling Technique (SMOTE) is demonstrated.

## Training

The following classification algorithms are trained and evaluated:

- Logistic Regression
- K Nearest Neighbors (KNN) Classifier
- Decision Tree Classifier
- Bagging Classifier with Decision Trees
- AdaBoost Classifier with Decision Trees
- Random Forest Classifier

## Performance Evaluation

Performance statistics and metrics are calculated including:

- Confusion Matrix
- Sensitivity (True Positive Rate)
- Specificity (True Negative Rate)
- Precision (Positive Predictive Value)
- Negative Predictive Value
- False Positive Rate
- False Negative Rate
- False Discovery Rate
- Accuracy
- AUC-ROC Curve

## Results

Random Forest Classifier yielded the best performance with an accuracy of 97.65% and an AUC of 0.97 on the validation set.

## Conclusion

This project showcases the application of machine learning techniques to EEG classification tasks, emphasizing the importance of handling imbalanced datasets for accurate predictions.
