# Credit Card Fraud Detection using Anomaly Detection

##  Project Overview
This project focuses on detecting fraudulent credit card transactions using unsupervised anomaly detection techniques. The dataset is highly imbalanced, with only a small percentage of transactions marked as fraud. The goal is to identify these rare fraudulent activities accurately.

##  Algorithms Used
- Isolation Forest
- Local Outlier Factor (LOF)

These models are well-suited for identifying anomalies in large datasets.

##  Dataset
- **Source:** [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Description:** Contains 284,807 transactions, with 492 labeled as fraud (0.17%).

##  Features Used
The dataset has 30 features:
- `V1` to `V28`: Result of PCA transformation
- `Time`: Seconds elapsed between each transaction and the first one
- `Amount`: Transaction amount
- `Class`: Target (0 = Legit, 1 = Fraud)

##  Steps Performed
1. Data loading and exploration
2. Data preprocessing (handling imbalance, checking correlation, scaling)
3. Model training:
   - Isolation Forest
   - Local Outlier Factor
4. Evaluation using:
   - Accuracy
   - Precision
   - Recall
   - Confusion Matrix

## Results
Both models were able to detect anomalies, with trade-offs between false positives and true fraud detection. Local Outlier Factor generally gave better precision.

##  File Structure
- `mini project.ipynb`: Main Jupyter Notebook with all code and outputs
- `README.md`: This file
- `creditcard.csv`: Dataset (if needed)

##  Conclusion
Anomaly detection is a powerful technique for identifying fraud in large datasets with imbalanced labels. The project demonstrates how simple unsupervised models can be effective in real-world applications.

##  Author
Suhani Jadhav
