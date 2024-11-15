# codsoft_taskno_2

# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. The model analyzes transaction data to classify transactions as either fraudulent or legitimate.

## Table of Contents
1. [Introduction](#introduction)  
2. [Dataset Overview](#dataset-overview)  
3. [Data Preprocessing](#data-preprocessing)  
4. [Model Building](#model-building)  
5. [Results and Evaluation](#results-and-evaluation)  
6. [Visualizations](#visualizations)  
7. [Dependencies](#dependencies)  
8. [Usage](#usage)  
9. [Contributor](#contributor)  

## Introduction  
Credit card fraud detection is a critical application in the financial sector that helps prevent financial losses and protect consumers. This project uses a dataset of credit card transactions to train a model that accurately identifies fraudulent activity.

## Dataset Overview  
- **Dataset:** The dataset used is the Credit Card Fraud Detection dataset, which contains 1,296,675 entries with the following columns:
  - `trans_date_trans_time`: Timestamp of the transaction.
  - `cc_num`: Credit card number.
  - `merchant`: Merchant name.
  - `category`: Category of the transaction.
  - `amt`: Transaction amount.
  - `gender`: Gender of the cardholder.
  - `city`: City where the transaction occurred.
  - `state`: State where the transaction occurred.
  - `zip`: Zip code of the transaction location.
  - `lat` and `long`: Latitude and longitude of the merchant location.
  - `merch_lat` and `merch_long`: Latitude and longitude of the merchant's address.
  - `is_fraud`: Indicates whether the transaction is fraudulent (1) or legitimate (0).
- **link of dataset** : https://www.kaggle.com/datasets/kartik2112/fraud-detection

## Data Preprocessing  
The following preprocessing steps are performed on the dataset:
1. **Loading Data**: The dataset is loaded using pandas.
2. **Data Cleaning**: Unnecessary columns are dropped, including those that are not relevant for predicting fraud (e.g., names, job titles).
3. **Handling Missing Values**: Check for null values and handle them appropriately.
4. **Feature Engineering**: Additional features may be created to enhance model performance.

## Model Building  
The model is built using the following steps:
1. **Splitting Data**: Divide the dataset into training and testing sets using train-test split.
2. **Model Selection**: Choose appropriate algorithms such as Decision Tree Classifier or Logistic Regression for classification tasks.
3. **Training**: Train the selected models on the training data.

## Results and Evaluation  
The performance of the model is evaluated using metrics such as:
- **Accuracy**: The proportion of correctly classified transactions.
- **Classification Report**: Includes precision, recall, and F1-score for both classes (fraudulent and legitimate).
- **Confusion Matrix**: To visualize true positives, false positives, true negatives, and false negatives.

## Visualizations  
Various visualizations are created to analyze the data:
- Distribution of legitimate vs fraudulent transactions.
- Correlation heatmaps to understand relationships between features.
- Bar charts to visualize transaction amounts by category.

## Dependencies  
To run this project, ensure you have the following libraries installed:
- Python 3.12
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

You can install these packages using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```
## Usage
**To use this project**:
- Clone this repository to your local machine.
- Ensure you have all dependencies installed.
- Run the Jupyter Notebook provided in this repository to execute the code and see results.
## Contributor
**Tejas Sinroja**: Project development, model design, and implementation.
- Feel free to contribute by suggesting improvements or reporting issues via GitHub!
