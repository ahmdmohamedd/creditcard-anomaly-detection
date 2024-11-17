# Credit Card Anomaly Detection

## Overview
This project implements anomaly detection techniques on a credit card transaction dataset. It utilizes machine learning and deep learning-based approaches to identify fraudulent transactions and anomalies. Several models are applied, including Random Forest, Isolation Forest, and Autoencoders for comprehensive detection.

## Features
- **Data Preprocessing**: Cleans and prepares the dataset for modeling.
- **Anomaly Detection Models**:
  - **Random Forest Classifier**: A supervised learning approach to detect anomalies.
  - **Isolation Forest**: An unsupervised algorithm designed for anomaly detection.
  - **Autoencoder**: A deep learning model used for detecting rare outliers in the data.
- **Evaluation**: Models are evaluated using precision, recall, F1 score, and average precision score.

## Dataset
The project uses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) which contains a mix of normal and fraudulent credit card transactions. The dataset includes 284,807 transactions with 31 features and a class imbalance of 0.17% fraudulent transactions.

## Setup
### Prerequisites
- Python 3.x
- Anaconda (recommended)
- Jupyter Notebook

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/creditcard-anomaly-detection.git
   ```
2. Navigate into the project directory:
   ```bash
   cd creditcard-anomaly-detection
   ```
3. Create and activate the Conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate neuralnetwork
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Open the Jupyter notebook:
   ```bash
   jupyter notebook anomaly_detection_creditcard.ipynb
   ```

## Models Used
1. **Random Forest Classifier**: A supervised method that uses decision trees to detect anomalies.
2. **Isolation Forest**: An unsupervised algorithm used for detecting anomalies by isolating outliers.
3. **Autoencoder Neural Network**: A deep learning-based approach for anomaly detection, using reconstruction error to identify rare events.

## Results
- Models are evaluated using metrics like F1 score, precision, and average precision score.
- Precision and recall metrics provide insights into how well the models identify anomalies and avoid false positives.
