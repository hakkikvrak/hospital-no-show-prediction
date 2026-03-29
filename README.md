

# Hospital No-Show Prediction

This project focuses on predicting whether a patient will miss a hospital appointment (no-show).

##  Project Goal

- Predict probability of patient no-show
- Optimize model for PR-AUC metric
- Build a clean machine learning pipeline

##  Dataset

This project uses a synthetic dataset created for a datathon scenario.

##  Model

- Model: CatBoostClassifier
- Validation: StratifiedKFold
- Metric: PR-AUC

##  Project Structure

hospital-no-show-prediction/
│
├── notebooks/
│   └── hospital-no-show-prediction.ipynb
├── src/
│   └── train_catboost.py
├── README.md
├── requirements.txt

##  How to Run

pip install -r requirements.txt
python src/train_catboost.py

##  Author

Hakkı Kıvrak
