<h1>Diabetes Detection </h1>

<h2>Introduction</h2>

This project is a diabetes detection app that uses Support Vector Machine (SVM) classification algorithm to predict whether a person is likely to have diabetes or not. The app takes as input a set of patient health data including demographic information, blood pressure, BMI, insulin level, etc. and returns a prediction of whether the patient is diabetic or not.

<h2>Use Case</h2>

When a patient is tested for diabetes thay have to go though a long line of tests to be able to correctly diagnose if they have diabetes or not. Our application uses data that takes into consideration the number of pregnancies, skin thickness, BMI, age, ect to make a prediciton about the patients health. This makes the process less tedious for the doctor and the patient.

<h2>SVM Model</h2>

The SVM model used in this app was trained using the preprocessed dataset and achieved an accuracy of 78%. The model was saved to a file called svm_model.sav using Python's joblib library and is loaded into memory when the app is started.

<h2>Dataset</h2>

The dataset used to train the SVM model was obtained from Kaggle and consists of health data for 768 patients, including whether or not they were diagnosed with diabetes. The data was preprocessed and cleaned to remove missing values and outliers.



