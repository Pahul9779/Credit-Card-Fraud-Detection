# Credit Card Fraud Detection

## Project Overview
This project aims to develop a machine learning model capable of detecting fraudulent credit card transactions. With the increasing prevalence of online financial transactions, identifying and preventing fraud is critical to protecting financial institutions and customers. The project leverages transaction data to classify transactions as fraudulent or legitimate.

## Features
- **Data Preprocessing**: Handled missing values and normalized transaction data.
- **Exploratory Data Analysis (EDA)**: Visualized transaction distributions, identifying trends and outliers.
- **Class Imbalance Handling**: Applied techniques such as oversampling and undersampling to balance the dataset.
- **Model Development**: Built, trained, and evaluated machine learning models to optimize classification accuracy.
- **Evaluation Metrics**: Used metrics like accuracy, precision, recall, F1-score, and ROC-AUC for assessment.

## Dataset
The dataset consists of anonymized transaction data and includes:
- **Time**: Seconds elapsed between transactions.
- **V1 to V28**: Principal components obtained using PCA.
- **Amount**: Transaction amount.
- **Class**: Target variable (0 = legitimate, 1 = fraudulent).

**Dataset Path:** Refer to the `Credit_Card_Fraud_Detection.ipynb` file for dataset details and preprocessing steps.

## Tools and Technologies
- **Programming Language**: Python  
- **Libraries**: 
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Imbalanced-learn  
- **Notebook**: Jupyter Notebook

## Project Files
- `Credit_Card_Fraud_Detection.ipynb`: The notebook containing data preprocessing, model building, and evaluation.
- `README.md`: Overview of the project.

## How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/Credit_Card_Fraud_Detection.git


## Install the required libraries:
bash
Copy code
pip install -r requirements.txt
Open the notebook:
bash
Copy code
jupyter notebook Credit_Card_Fraud_Detection.ipynb
Run the cells in order.

##Results
The model achieved:

- Accuracy: 99%
- Precision: 94%
- Recall: 90%
- F1-Score: 92%
- ROC-AUC Score: 97%
