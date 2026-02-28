# California-Housing-Price-Prediction-System
A production-ready Machine Learning regression system that predicts California housing prices using structured real estate data. This project demonstrates a complete ML workflow including preprocessing, stratified sampling, model training, evaluation, model persistence, and inference.

## 1 Data Preprocessing:
 1.Stratified sampling based on income category
 2.Missing value imputation using median strategy
 3.Feature scaling using StandardScaler
 4.One-hot encoding for categorical features.
 5.ColumnTransformer for structured feature handling

## 2️ Model Training:
 1.RandomForestRegressor
 2.10-fold Cross Validation
 3.Evaluation using Root Mean Squared Error (RMSE)

## 3️ Model Persistence:
 1.Saves trained model as model.pkl
 2.Saves preprocessing pipeline as pipeline.pkl
 3.Avoids retraining if model already exists

## 4️ Inference Workflow:
 1.Loads saved model and pipeline
 2.Transforms unseen input data 
 3.Generates predictions
 4.exports predictions to output.csv
 
