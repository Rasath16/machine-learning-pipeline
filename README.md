# TCustomer Churn Prediction Pipeline

This project implements a comprehensive machine learning pipeline to predict customer churn for a telecom company. It includes data preprocessing, model training, cross-validation, hyperparameter tuning, and threshold optimization to maximize predictive performance.

## Project Structure

- `0_data_preperation.ipynb`: Preprocessing raw data, handling missing values, feature engineering, and encoding.
- `1_base_model_training.ipynb`: Training initial models to evaluate baseline performance.
- `2_kfold_validation.ipynb`: Using K-Fold cross-validation to assess model generalization.
- `3_multi_model_training.ipynb`: Comparing multiple models (e.g., Logistic Regression, Random Forest, XGBoost).
- `4_hyperparam_tuning.ipynb`: Fine-tuning hyperparameters to improve performance.
- `5_threshold_optimization.ipynb`: Optimizing classification threshold for better metrics like F1-score or ROC-AUC.
- `artifacts/`: Preprocessed train and test datasets.
- `data/processed/`: Cleaned and transformed CSV datasets.
- `requirements.txt`: Python dependencies for running the notebooks.
