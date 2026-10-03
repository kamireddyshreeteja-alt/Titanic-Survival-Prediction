# Titanic Survival Prediction

## 📌 Project Overview
This project predicts whether a passenger survived the Titanic disaster using Machine Learning.

The Titanic dataset was analyzed, preprocessed, visualized, and used to train classification models.

## 📊 Dataset
The dataset contains information about Titanic passengers, including:
- Passenger class
- Sex
- Age
- Fare
- Number of siblings/spouses
- Number of parents/children
- Embarkation details

## 🔧 Data Preprocessing
The following steps were performed:
- Checked and handled missing values
- Encoded categorical variables
- Transformed features
- Standardized numerical features
- Split the dataset into training and testing sets

## 🤖 Machine Learning Models
Three classification models were trained and compared:
1. Logistic Regression
2. Decision Tree
3. Random Forest

## 📈 Model Evaluation
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Logistic Regression achieved an accuracy of approximately **81.01%** on the test data.

## 💾 Model Saving
The trained Logistic Regression model was saved using Joblib as:

`LogisticRegression.joblib`

The saved model was loaded again and used to make predictions successfully.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## 👩‍💻 Project Author
Shree Teja K
