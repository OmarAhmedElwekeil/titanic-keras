# Titanic Survival Prediction using Keras

## 📌 Overview
This project predicts whether a passenger survived the Titanic disaster using a Neural Network built with **Keras**.  
It uses the Titanic dataset, processes the features, encodes categorical variables, scales numerical values, and trains a classification model.

## 📂 Dataset
- Dataset: Titanic dataset from Kaggle (`train.csv`)
- Target: `Survived` (0 = Did not survive, 1 = Survived)

## ⚙️ Features Used
- **pclass**: Passenger class (1, 2, 3)
- **age**: Passenger age
- **sibsp**: Number of siblings/spouses aboard
- **parch**: Number of parents/children aboard
- **fare**: Ticket fare
- **adult_male**: Whether the passenger is an adult male (True/False)
- **alone**: Whether the passenger was alone (True/False)
- **sex_male**: Gender encoded as 1 for male, 0 for female
- **embarked_Q**: Embarked from Queenstown (binary)

## 🧠 Model Details
- Framework: **Keras** with TensorFlow backend
- Model Type: **Sequential Neural Network**
- Activation Functions: `ReLU` for hidden layers, `Sigmoid` for output
- Optimizer: `Adam`
- Loss Function: `binary_crossentropy`
- Metrics: `accuracy`
- Data Split: 80% training, 20% validation
- Training Parameters:
  - **Epochs**: 50
  - **Batch Size**: 32
  - **Validation Split**: 0.2

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn tensorflow
