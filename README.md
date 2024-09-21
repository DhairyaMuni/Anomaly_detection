# Anomaly Detection in Credit Card Transactions

## Description
This project aims to predict fraudulent credit card transactions using anomaly detection techniques. By identifying unusual patterns in transaction data, the system helps in detecting potentially fraudulent transactions, preventing financial losses. The solution leverages unsupervised learning models, including **Isolation Forest**, **Local Outlier Factor (LOF)**, and **One-Class SVM**.

## Concepts and Techniques
- **Anomaly Detection**: A method to identify rare items, events, or observations that differ significantly from the majority of the data.
- **Unsupervised Learning**: Since we lack labeled data, we apply models that do not require labeled training data to learn the patterns in the dataset.
- **Isolation Forest**: Anomaly detection method that isolates observations by randomly selecting a feature and splitting it based on a random threshold. Anomalies are easier to isolate and have shorter paths.
- **Local Outlier Factor (LOF)**: Measures the local density deviation of a given data point concerning its neighbors.
- **One-Class SVM**: A support vector machine algorithm used for outlier detection in high-dimensional spaces.

## Dataset
The project utilizes a dataset of credit card transactions. Each transaction is represented by various features (e.g., transaction amount, date, location, etc.), and the goal is to identify anomalous or suspicious transactions.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Anomaly-Detection.git
   cd Anomaly-Detection
2. Install the required dependencies:
   ```bash
   pip install  -r requirements.txt


##DATASET:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
