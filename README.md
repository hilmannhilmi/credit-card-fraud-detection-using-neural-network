# Project Title: Credit Card Fraud Detection Using Neural Networks

## Project Overview:
Credit card fraud poses a significant threat to both financial institutions and cardholders. Detecting fraudulent transactions in real-time is crucial to minimize losses. In this project, we have developed a robust credit card fraud detection system using deep learning techniques.

## Key Steps and Components:

### Data Preprocessing:
- We start by importing the necessary libraries and loading the credit card transaction dataset.
- Standardization is applied to the 'Amount' feature to ensure that all input features have the same scale.
- Unnecessary columns like 'Amount' and 'Time' are dropped from the dataset.

### Data Splitting:
The data is split into training and testing sets to train and evaluate the model's performance.

### Neural Network Architecture:
- We create a deep neural network using the Keras library.
- The architecture includes multiple layers of densely connected neurons.
- Dropout layers are included to prevent overfitting.

### Training the Model:
- The model is compiled using the Adam optimizer and binary cross-entropy loss function.
- It is then trained on the training data, and training results are monitored.

### Model Evaluation:
- We evaluate the model's performance on a test dataset.
- A confusion matrix is generated to assess the model's ability to correctly classify fraud and non-fraud transactions.

### Handling Class Imbalance:
- To address the class imbalance problem common in fraud detection, we perform under-sampling of the majority class and oversampling of the minority class.
- SMOTE (Synthetic Minority Over-sampling Technique) is used to oversample the minority class.

### Re-training the Model with Balanced Data:
- The model is re-trained with the balanced dataset to improve its ability to detect fraud cases.

### Final Model Evaluation:
- We assess the model's performance on the balanced dataset and visualize the confusion matrix.

### Results:
- The initial model shows promising results in detecting credit card fraud, achieving a high accuracy rate during training at 99.76%.
- After addressing class imbalance, the model's performance is further improved, enhancing its ability to detect fraudulent transactions.
- The model is then improved from having 30 false positives to 2 in the testing datasets.

### Conclusion:
This credit card fraud detection project showcases the effectiveness of deep learning techniques in identifying fraudulent activities. The use of neural networks, data preprocessing, and class balancing strategies has resulted in a robust fraud detection system. The project serves as a valuable resource for financial institutions and organizations seeking to enhance their fraud prevention measures.

Feel free to adapt and extend this project to tackle similar challenges in the domain of fraud detection and security.
