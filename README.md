# Credit Card Fraud Detection Using Logistic Regression

<h2>Overview</h2>

This project builds a machine learning model to detect fraudulent credit card transactions. Fraud detection is a critical problem in the financial industry because fraudulent transactions represent a very small percentage of all transactions but can cause significant financial losses.

<h2>Dataset</h2>

The dataset contains credit card transactions with features representing transaction characteristics.

Key details:

Transactions are labeled as:

0 → Legitimate transaction

1 → Fraudulent transaction

The dataset is highly imbalanced, with far fewer fraud cases than normal transactions.

Most features are numerically transformed variables for privacy reasons.

Kaggle Link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

<h2>Data Preprocessing</h2>
Handling Class Imbalance: Because the dataset is heavily skewed toward legitimate transactions, random undersampling was used.

Undersampling works by:

<li>Keeping all fraudulent transactions</li>
<li>Randomly selecting an equal number of legitimate transactions</li>

This creates a balanced dataset, allowing the model to learn patterns from both classes more effectively.

<h2>Model Workflow</h2>

<li>Load and explore the dataset</li>
<li>Check class distribution</li>
<li>Apply undersampling to balance the dataset</li>
<li>Split the data into training and testing sets</li>
<li>Train a Logistic Regression model</li>
<li>Evaluate model performance on the test set</li>

<h2>Model Evaluation</h2>

The model performance was evaluated using: Accuracy Score

Accuracy measures the proportion of correctly predicted transactions.
<h2>Conclusion</h2>

This project demonstrates the application of Logistic Regression for credit card fraud detection in a highly imbalanced dataset. Because fraudulent transactions represent only a small portion of the data, random undersampling was applied to balance the dataset and improve the model’s ability to learn patterns associated with fraud.

After training the model, the following performance results were obtained:

<li>Training Accuracy: 0.9502</li>

<li>Test Accuracy: 0.9717</li>

These results show that the model performs well in distinguishing between fraudulent and legitimate transactions, achieving high accuracy on both training and test datasets.
