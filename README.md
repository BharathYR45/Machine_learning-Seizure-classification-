# Machine learning Project(Seizure classification)

Title 
**"Epileptic Seizure Classification - A Deep Learning Approach"**

**Project Overview**

This project aims to detect and classify epileptic seizures using a deep learning approach. By leveraging modified Convolutional Neural Networks (CNNs), the model achieves high accuracy in distinguishing between seizure and non-seizure events based on EEG data.

**Abstract**

Epileptic seizure disorder is characterized by recurrent seizures due to abnormal brain activity. This project utilizes a modified CNN for seizure detection and classification, achieving a testing classification accuracy of 98% and a validation accuracy of 97%. The model's architecture includes batch normalization, dense layers with ReLU activation, and dropout layers to capture complex EEG patterns and prevent overfitting.

**Dataset details**

The dataset consists of EEG recordings from 500 individuals, each monitored for 23.6 seconds. Each recording is divided into 23 segments of 178 data points, resulting in 11,500 data pieces. The EEG recordings are classified into five categories:
Seizure activity
Tumor presence
Healthy brain region activity
Eyes closed
Eyes open

**Model Architecture**

The CNN model includes:
Input layer with 178 features
Three dense layers with sizes 256, 512, and 1024
Batch normalization and dropout layers for stable and accelerated training
Output layer for binary classification

**Methodology**

Data Preprocessing: Data normalization and oversampling to balance the dataset.
Data Splitting: 80% for training and 20% for testing.
Model Training: Using Nvidia RTX A6000 GPU for accelerated training.
Evaluation: High precision, recall, and F1-score across seizure and non-seizure classifications.

**Results**

- **Accuracy:** 98%  
- **Validation Loss:** 3.89%  
- **Confusion Matrix:** High sensitivity and specificity with minor misclassification.  
- **Evaluation Metrics**  
- **Precision:** 0.98
- **Recall:** 0.97  
- **F1-score:** 0.97
- **Macro Average:** 0.97  
- **Weighted Average:** 0.97

You can access the research paper here"https://drive.google.com/file/d/1hmZu43pdrRD9OVxPKLmqoUWRg3-flY9N/view?usp=sharing""
