
Parkinson's Disease Diagnosis Using Voice Data
Abstract
This project presents a comparative analysis of two supervised machine learning models K-Nearest Neighbors (KNN) and Support Vector Classifier (SVC) for diagnosing Parkinson's Disease (PD) using voice-based features.

•	The dataset includes 195 records and 24 voice features, such as frequency (Hz), jitter, shimmer, and noise-to-harmonic ratio.
•	Since KNN and SVM are sensitive to feature scaling, preprocessing is crucial due to the varying units in voice features.
•	The target variable indicates whether the individual has PD (1) or not (0).
•	To handle class imbalance, the Stratified Shuffle Split (SSS) technique was used to ensure proportional label distribution in both training and testing sets.
•	Hyperparameter tuning was performed for both models.
•	Evaluation metrics included: accuracy, precision, recall, F1-score, and ROC-AUC.

Key Results:
Both KNN and SVC showed similar accuracy and precision metrics.

However, ROC-AUC revealed notable differences:

•	KNN AUC: 0.85 (good)
•	SVC AUC: 0.99 (excellent)
•	SVC demonstrated superior classification performance overall.
•	Visualizations (confusion matrices, bar charts, and ROC curves) were used to support these findings.

Introduction
Parkinson's Disease (PD) is a progressive neurological disorder that affects movement and various non-motor functions. According to research:

•	PD affects approximately 1% of individuals over 60.
•	The global PD population increased from 2.5 million in 1990 to 6.1 million in 2016 (Dorsey et al., 2018).
•	Symptoms impact multiple areas including motor planning, initiation, and execution (Contreras Vidal & Stelmach, 1995).
•	While traditional diagnosis methods exist, voice analysis has emerged as a promising non-invasive method for early detection.

This project explores the effectiveness of KNN and SVC models in diagnosing PD using a labeled dataset of voice features. The goal is to evaluate the classification performance of each model using a consistent set of evaluation metrics and draw insights on their strengths and limitations.
