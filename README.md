# Credit-Card-Fraud-Detection-with-Isolation-Forest-Autoencoders

# Credit Card Fraud Detection

This project detects fraudulent credit card transactions using machine learning techniques including Isolation Forest and Autoencoder Neural Networks.

## Dataset

- Source: [Kaggle - Credit Card Fraud Detection]: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- The dataset contains transactions made by European cardholders in September 2013.

## Models Used

- **Isolation Forest**: Treats fraud as anomalies.
- **Autoencoder**: Detects fraud based on reconstruction error.

## How to Run

1. Download the dataset from Kaggle: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud and place `creditcard.csv` in your project directory.
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn tensorflow

/Fraud-Detection  
│── /models  
│   │── isolation_forest.pkl  
│   │── autoencoder.h5  
│── Fraud_Detection.ipynb (with interactive plots)  
│── README.md (compare both methods' precision/recall)
