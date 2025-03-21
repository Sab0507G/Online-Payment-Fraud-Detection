# Online-Payment-Fraud-Detection

## Introduction
Online payment is the most popular transaction method in the world today. However, with the increase in online payments, there has also been a rise in payment fraud. Fraudulent transactions can cause significant financial losses, making fraud detection a critical challenge in the financial sector. The objective of this project is **to identify fraudulent and non-fraudulent payments** using machine learning techniques.

## Dataset
The dataset is sourced from Kaggle and contains historical information about online transactions. This data can be used to develop models capable of detecting fraudulent transactions.

### Features:
- **step**: Represents a unit of time where 1 step equals 1 hour.
- **type**: Type of online transaction (e.g., CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER).
- **amount**: The amount of the transaction.
- **nameOrig**: Customer initiating the transaction.
- **oldbalanceOrg**: Balance before the transaction.
- **newbalanceOrig**: Balance after the transaction.
- **nameDest**: Recipient of the transaction.
- **oldbalanceDest**: Initial balance of the recipient before the transaction.
- **newbalanceDest**: New balance of the recipient after the transaction.
- **isFraud**: Indicates whether the transaction was fraudulent (1) or not (0).

## Methodology
To detect fraudulent transactions, we will use various machine learning techniques, including:
- **Exploratory Data Analysis (EDA)**: To understand patterns and relationships within the dataset.
- **Feature Engineering**: Creating new features and handling missing values.
- **Machine Learning Models**:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Gradient Boosting (XGBoost, LightGBM)
  - Neural Networks

## Results
- Model performance will be evaluated using Accuracy, Precision, Recall, and F1-score.
- Confusion Matrix will be used to visualize fraud detection.

## Future Work
- Implement deep learning techniques such as LSTMs.
- Use real-time fraud detection techniques with streaming data.
- Improve model interpretability using SHAP or LIME.

## Conclusion
This project aims to build an effective fraud detection system using machine learning. By analyzing transaction data, we can identify patterns and improve fraud detection accuracy.

## Acknowledgments
- Kaggle for providing the dataset.
- Open-source ML communities for guidance and support.

