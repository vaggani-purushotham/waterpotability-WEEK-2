

# Water Potability Prediction:

This project predicts whether water is potable or not using machine learning models. The dataset includes various water quality indicators such as pH, hardness, solids, chloramines, sulfate, conductivity, and trihalomethanes.


# Dataset:

Source: Kaggle - Water Potability Dataset

Rows: 3,276 samples

Target Column: Potability (1 = Safe to Drink, 0 = Not Safe)


# Workflow:

1.DATA EXPLORATION & VISUALIZATION:

Null values check & handling (median imputation).

Correlation heatmap, histograms, scatter plots, and box plots.


2.PREPROCESSING:

Train-test split (70-30).

Standardization using StandardScaler.


3.MODELS TRAINED:

Logistic Regression

Random Forest

Bagging Classifier

AdaBoost Classifier

Gradient Boosting Classifier

Support Vector Classifier (SVC)

XGBoost Classifier


4.EVALUATION METRICS:

Accuracy Score

Precision Score

Confusion Matrix (heatmap)

KDE plot (Actual vs Predicted distribution)


5.RESULTS:

Compared performance of multiple ML models.

Best model can be chosen based on Accuracy & Precision.

# How to Run
# Clone this repo
git clone https://github.com/vaggani-purushotham/water-potability-prediction.git

cd water-potability-prediction

# Install dependencies
pip install -r requirements.txt

# Run the notebook in Google Colab / Jupyter
