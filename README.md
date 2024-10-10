# Epileptic Seizure Classification - A Deep Learning Approach ⚡

## Project Overview

This project aims to detect and classify epileptic seizures using a deep learning approach. By leveraging modified Convolutional Neural Networks (CNNs), the model achieves high accuracy in distinguishing between seizure and non-seizure events based on EEG data.

## Abstract

Epileptic seizure disorder is characterized by recurrent seizures due to abnormal brain activity. This project utilizes a modified CNN for seizure detection and classification, achieving a testing classification accuracy of **98%** and a validation accuracy of **97%**. The model's architecture includes batch normalization, dense layers with ReLU activation, and dropout layers to capture complex EEG patterns and prevent overfitting.

## Dataset Details 📊

- **Source:** EEG recordings from 500 individuals, each monitored for 23.6 seconds.
- **Segments:** Each recording is divided into 23 segments of 178 data points, resulting in a total of **11,500 data pieces**.
- **Categories:** The EEG recordings are classified into five categories:
  - Seizure activity
  - Tumor presence
  - Healthy brain region activity
  - Eyes closed
  - Eyes open

- **Dataset Link:** [Epileptic Seizure Recognition Dataset](https://www.kaggle.com/datasets/harunshimanto/epileptic-seizure-recognition)

## Model Architecture 🏗️

The CNN model includes:
- **Input Layer:** 178 features
- **Dense Layers:** Three layers with sizes 256, 512, and 1024
- **Regularization:** Batch normalization and dropout layers for stable and accelerated training
- **Output Layer:** For binary classification

## Methodology 🛠️

1. **Data Preprocessing:** Normalization and oversampling to balance the dataset.
2. **Data Splitting:** 80% for training and 20% for testing.
3. **Model Training:** Utilized an Nvidia RTX A6000 GPU for accelerated training.
4. **Evaluation:** Achieved high precision, recall, and F1-score across seizure and non-seizure classifications.

## Results 🎯

- **Accuracy:** 98%
- **Validation Loss:** 3.89%
- **Confusion Matrix:** High sensitivity and specificity with minor misclassification.

### Evaluation Metrics:
- **Precision:** 0.98
- **Recall:** 0.97
- **F1-score:** 0.97
- **Macro Average:** 0.97
- **Weighted Average:** 0.97

You can access the published paper here: [Epileptic Seizure Classification - A Deep Learning Approach](https://ieeexplore.ieee.org/document/10649060)

## About 📖

This project demonstrates the application of deep learning techniques to enhance the accuracy of epileptic seizure detection, ultimately aiming to improve patient care and diagnosis.

## Resources 📚

- **Readme**: Comprehensive documentation for the project.
- **License**: MIT License for open-source use.



## Technologies Used 💻

- **Language:** python (100.0%)
- **Tool used:** google colab

---

Feel free to contribute to this project by forking the repository and creating pull requests. All contributions are welcome!

