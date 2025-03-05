# Fraud Detection

## Project Overview
This project focuses on detecting fraudulent transactions using machine learning models. Various classification techniques, including Random Forest, XGBoost, and Isolation Forest, are applied to identify fraudulent activities in the dataset.

## Dataset
The dataset consists of transaction records, with labels indicating whether a transaction is fraudulent (1) or legitimate (0). The dataset is highly imbalanced, with significantly fewer fraudulent cases compared to legitimate ones.

## Models Used
1. **Random Forest**
2. **XGBoost**
3. **Isolation Forest**

## Model Performance

### Random Forest
- Precision: **1.00 (Class 0), 0.29 (Class 1)**
- Recall: **0.99 (Class 0), 0.91 (Class 1)**
- F1-score: **1.00 (Class 0), 0.44 (Class 1)**
- Accuracy: **0.44**

### XGBoost
- Precision: **1.00 (Class 0), 0.60 (Class 1)**
- Recall: **1.00 (Class 0), 0.91 (Class 1)**
- F1-score: **1.00 (Class 0), 0.72 (Class 1)**
- Accuracy: **0.85**

### Isolation Forest
- Precision: **1.00 (Class 0), 0.38 (Class 1)**
- Recall: **1.00 (Class 0), 0.18 (Class 1)**
- F1-score: **1.00 (Class 0), 0.24 (Class 1)**
- Accuracy: **0.24**

### Additional Metrics
- **AUC-PR (Area Under Precision-Recall Curve):** 0.85

## Dependencies
To run this project, install the required dependencies using:
```bash
pip install -r requirements.txt
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/nba26/fraud-detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd fraud-detection
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook FraudDetection.ipynb
   ```

## Conclusion
XGBoost performed the best among the models, with the highest accuracy (85%) and a strong AUC-PR score (0.85). The Random Forest model showed a high recall for fraudulent transactions but had lower precision, while the Isolation Forest performed the worst due to its lower recall for fraudulent transactions.

