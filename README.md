**Credit Card Fraud Detection Using Artificial Neural Networks (ANN)**

**Overview**
This project aims to detect fraudulent credit card transactions using an Artificial Neural Network (ANN). The dataset consists of anonymized credit card transactions, with a binary label indicating whether a transaction is fraudulent or legitimate.

By training a neural network model, the project focuses on identifying patterns that distinguish between fraudulent and non-fraudulent transactions. Fraud detection is crucial in the financial sector as it helps reduce the risk of financial loss and ensures secure transactions.

**Datasheet **:
Source: https://drive.google.com/file/d/1FjfdrnvCDcGhcfo94d0U6WJDay4v2rFq/view?usp=drive_link
Features: The dataset includes several anonymized features representing different aspects of credit card transactions.
Time: Time elapsed since the first transaction.
V1 to V28: Principal components obtained from PCA transformation.
Amount: Transaction amount.
Class: Target label, where 1 indicates fraud and 0 indicates a legitimate transaction.

**Data Preprocessing**
Data normalization or standardization is applied to ensure that the ANN model performs optimally.
The dataset is imbalanced, so methods like resampling or using class weights may be implemented to address this issue.

**Artificial Neural Network (ANN) Model**
Input Layer: The features from the dataset are passed as inputs to the model.
Hidden Layers: One or more fully connected hidden layers, with activation functions like ReLU.
Output Layer: A single node with a sigmoid activation function to output a probability for binary classification (fraud or not fraud).

**Hyperparameters**
Optimizer: Adam
Loss Function: Binary Crossentropy
Metrics: Accuracy, Precision, F1 Score
Batch Size: 100
Epochs: 100 (modifiable based on model performance)
Confusion Matrix: The confusion matrix is used to visualize the performance of the classification model by comparing predicted and actual values.
