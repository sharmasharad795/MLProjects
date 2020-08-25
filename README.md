# MLProjects
Projects done as part of the machine learning course taken at USC

1) NormalAbnormalBones - Each patient in the data set is represented in the data set
by six biomechanical attributes derived from the shape and orientation of the pelvis
and lumbar spine (in this order): pelvic incidence, pelvic tilt, lumbar lordosis angle,
sacral slope, pelvic radius and grade of spondylolisthesis.

K Nearest Neighbors is used to then classify between normal and abnormal bone conditions. Different distance metrics are employed to test the difference in results.


2) Cycle Power Plant - Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP),
Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical
energy output (EP) of the plant. 

Apart from data analysis, regression algorithms such as simple linear regression, Multiple regression, KNN regression are used.


3) TimeSeriesClassification - In this problem,
we will classify the activities of humans based on time series obtained by a Wireless
Sensor Network.

Feature extraction is performed first. Algorithms such as Logistic Regression, RFE, L1 penalized Logistic Regression, Multi Class classification, Naive Bayes ( both Gaussian and multinomial )


4) APSFailure - This project applies SMOTE to a seriously imbalanced dataset
with a large number of features and data points. 

Random Forest and Logistic Model Trees (LMT) (using Weka) are used for the classification task. SMOTE Is used to deal with the class imabalance.

Additionally, this project also works on communities and crime data using Lasso and Ridge Regression, PCR and XGBoost models.



5) FrogAnuranCallsClassification - In this project, we wish to classify the calls made by frogs (during mating season) .Each instance has three labels: Families, Genus, and Species. Each of the labels has multiple classes. We wish to solve a multi-class and multi-label problem.

Different approaches are used for this problem which include : L1 Penalized SVMs, one vs all classifier strategy, and K Means clustering



6) BreastCancerPrediction - Classification between benign and malignant tumors using FOUR differenet approaches : 
    Supervised learning using L1 Penalised SVM
    Self training coupled with L1 penalised SVM
    Unsupervised learning using Spectral and K means clustering
    Active learning using SVM
