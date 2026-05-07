💳 Credit Card Fraud Detection System

DataSet Link: https://www.kaggle.com/datasets/ankitkumarchaubey1/credit-card-dataset

📌 Project Overview

This project focuses on detecting fraudulent financial transactions using machine learning and anomaly detection techniques.

The workflow includes:
- Data preprocessing
- Feature engineering
- Handling imbalanced datasets
- Model training and evaluation
- Explainable AI using SHAP

The project compares multiple fraud detection approaches:
- Logistic Regression
- Autoencoder Neural Network
- XGBoost Classifier

🎯 Objectives

- Detect fraudulent transactions accurately
- Handle highly imbalanced transaction data
- Compare machine learning and deep learning models
- Improve fraud detection using resampling techniques
- Interpret predictions using SHAP explainability

📁 Dataset

Dataset file used in the project:
- frauddataset

Important attributes include:
- Transaction date and time
- Merchant information
- Customer details
- Transaction amount
- Geographic information

🧹 Data Preprocessing

The following preprocessing steps were performed:
- Missing value handling
- Datetime conversion
- Feature extraction from timestamps
- Encoding categorical variables
- Feature scaling using StandardScaler
- Train-test splitting

⚙️ Feature Engineering

Time-based Features:
- Transaction hour
- Day of week

Customer-based Features:
- Customer age
- Transaction behavior patterns

Additional Features:
- Reconstruction error from Autoencoder
- Encoded categorical variables

⚖️ Handling Imbalanced Data

Since fraud datasets are highly imbalanced, the following techniques were applied:
- class_weight='balanced'
- SMOTE oversampling
- Random undersampling
- Hybrid resampling pipeline using imblearn

🤖 Models Used

1. Logistic Regression
- Baseline supervised classification model
- Trained on balanced and unbalanced data

2. Autoencoder
- Deep learning anomaly detection model
- Uses reconstruction error to detect anomalies

3. XGBoost Classifier
- Gradient boosting model for optimized fraud detection

📊 Evaluation Metrics

The following metrics were used:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- AUPRC
- Confusion Matrix

📈 Explainability

SHAP (SHapley Additive Explanations) was used for:
- Global feature importance
- Transaction-level explanation
- Model interpretability

🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- Imbalanced-learn
- SHAP
- Matplotlib
- Seaborn

📂 Project Structure
Untitled-1.ipynb
README.md


🚀 Installation & Setup

-Clone Repository

-Install Dependencies
-pip install pandas numpy scikit-learn xgboost tensorflow imbalanced-learn shap matplotlib seaborn

-Run Notebook

jupyter notebook

▶️ Usage

1. Open the notebook file
2. Run cells sequentially
3. Train and evaluate models
4. Analyze fraud detection performance and SHAP explanations

📌 Key Highlights

- End-to-end fraud detection pipeline
- Imbalanced data handling using SMOTE
- Machine learning and deep learning implementation
- Explainable AI using SHAP
- Multiple model comparison

⚠️ Limitations

- Performance depends on dataset quality
- Requires higher computational resources for deep learning
- Additional tuning can improve performance

🔮 Future Improvements

- Real-time fraud detection system
- Deployment using Flask/FastAPI
- Advanced deep learning architectures
- Hyperparameter optimization
