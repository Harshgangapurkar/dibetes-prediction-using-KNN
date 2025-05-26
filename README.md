🧠 K-Nearest Neighbors (KNN) Classifier on Diabetes Dataset
This repository contains a simple machine learning pipeline using the K-Nearest Neighbors (KNN) algorithm to classify diabetes outcomes based on patient health metrics. The model is built and evaluated using scikit-learn, and includes steps such as preprocessing, model tuning, and performance evaluation.

📁 Files
diabetes.csv: Dataset containing health records and diabetes outcome.

diabetes prediction by KNN(1).ipynb: Jupyter Notebook with full implementation of the KNN pipeline.


📊 Dataset Description
The dataset includes the following features:

Pregnancies: Number of times pregnant

Glucose: Plasma glucose concentration

BloodPressure: Diastolic blood pressure (mm Hg)

SkinThickness: Triceps skinfold thickness (mm)

Insulin: 2-Hour serum insulin (mu U/ml)

BMI: Body mass index (weight in kg/(height in m)^2)

DiabetesPedigreeFunction: A function which scores likelihood of diabetes based on family history

Age: Age in years

Outcome: Diabetes presence (1 = True, 0 = False)

🛠️ Model Pipeline
Importing Libraries
pandas, scikit-learn, matplotlib, seaborn, etc.

Loading Dataset
Reads the diabetes.csv file into a pandas DataFrame.

Preprocessing

Feature scaling with StandardScaler

Dataset inspection (info(), head(), etc.)

Model Training

Trains a KNeighborsClassifier

Classification report


📈 Output Example
Sample classification report:
mark
                 precision    recall  f1-score   support

           0       0.82      0.85      0.83       50
           1       0.78      0.74      0.76       50

    accuracy                           0.79      100
   macro avg       0.80      0.79      0.79      100
weighted avg       0.80      0.79      0.79      100
