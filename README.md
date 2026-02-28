# California-Housing-Price-Prediction-System
A production-ready Machine Learning regression system that predicts California housing prices using structured real estate data. This project demonstrates a complete ML workflow including preprocessing, stratified sampling, model training, evaluation, model persistence, and inference.

## 1 Data Preprocessing:
 - Stratified sampling based on income category
 - Missing value imputation using median strategy
 - Feature scaling using StandardScaler
 - One-hot encoding for categorical features.
 - ColumnTransformer for structured feature handling

## 2️ Model Training:
 - RandomForestRegressor
 - 10-fold Cross Validation
 - Evaluation using Root Mean Squared Error (RMSE)

## 3️ Model Persistence:
 - Saves trained model as model.pkl
 - Saves preprocessing pipeline as pipeline.pkl
 - Avoids retraining if model already exists

## 4️ Inference Workflow:
 - Loads saved model and pipeline
 - Transforms unseen input data 
 - Generates predictions
 - exports predictions to output.csv
 
