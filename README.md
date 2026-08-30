# Classification-of-microscopic-blood-cells-using-Machine-Learning

## Overview

This project focuses on the automated classification of microscopic blood cell images using deep learning and computer vision techniques. The system is designed to classify different white blood cell (WBC) types from microscopic blood smear images with high accuracy.

The project uses Convolutional Neural Networks (CNNs), image preprocessing, feature extraction, and deep learning techniques to improve the efficiency and reliability of hematological analysis.

The model classifies the following blood cell categories:

- Eosinophil
- Lymphocyte
- Monocyte
- Neutrophil

---

## Problem Statement

Traditional microscopic blood cell analysis is performed manually by hematologists and laboratory technicians. This process is:

- Time-consuming
- Labor-intensive
- Prone to human error
- Difficult to scale for large datasets

The proposed machine learning-based system automates blood cell classification to improve diagnostic accuracy, consistency, and efficiency.

---

## Features

- Automated microscopic blood cell classification
- Deep learning-based image analysis
- Custom CNN architecture
- Local and global feature extraction
- Image preprocessing and augmentation
- Confusion matrix and ROC curve evaluation
- Prediction on unseen microscopic blood cell images

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Dataset

The dataset consists of microscopic blood cell images categorized into four classes:

| Class ID | Blood Cell Type |
|---|---|
| 0 | Eosinophil |
| 1 | Lymphocyte |
| 2 | Monocyte |
| 3 | Neutrophil |

### Dataset Preprocessing

The following preprocessing techniques were applied:

- Grayscale conversion
- Image resizing to 128x128
- Normalization
- Data augmentation
- Data shuffling
- Train-validation-test splitting

---

## Model Architecture

The project implements a custom deep learning architecture using:

- Convolutional Neural Networks (CNNs)
- Depthwise Convolutions
- Batch Normalization
- Max Pooling
- Dense Layers
- Softmax Classification

The architecture combines:

- Local Feature Extraction Network
- Global Feature Extraction Network
- Patch Extraction Layer
- Cosine Similarity-based Feature Fusion

---

## Training Configuration

| Parameter | Value |
|---|---|
| Optimizer | Nadam |
| Learning Rate | 0.0001 |
| Loss Function | Categorical Crossentropy |
| Batch Size | 16 |
| Epochs | 100 |
| Input Size | 128x128 |
| Activation Function | ReLU / Softmax |

---

## Evaluation Metrics

The model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- AUC Score

---

## Results

The model achieved strong classification performance on microscopic blood cell images.

### Key Achievements

- Achieved over 95% classification accuracy
- Successfully classified four major white blood cell types
- Reduced analysis time compared to manual microscopic analysis
- Improved classification consistency and reliability

---

## Project Structure

bash Classification-of-microscopic-blood-cells-using-Machine-Learning/ │ ├── dataset/ ├── blood_cell_classification.ipynb ├── requirements.txt ├── README.md └── .gitattributes 

---

## Installation

Clone the repository:

bash git clone https://github.com/lalithtejakarnati/Classification-of-microscopic-blood-cells-using-Machine-Learning.git 

Navigate to the project directory:

bash cd Classification-of-microscopic-blood-cells-using-Machine-Learning 

Install required dependencies:

bash pip install -r requirements.txt 

---

## Running the Project

Start Jupyter Notebook:

bash jupyter notebook 

Open:

bash blood_cell_classification.ipynb 

Run all cells to train and evaluate the model.

---

## Sample Workflow

1. Load blood cell image dataset
2. Preprocess images
3. Train CNN model
4. Validate model performance
5. Predict blood cell classes
6. Evaluate results using confusion matrix and ROC curves

---

## Future Improvements

- Deploy as a web application
- Add real-time prediction support
- Integrate transfer learning models such as ResNet and EfficientNet
- Improve model interpretability using Grad-CAM
- Expand dataset with additional blood disorders

---

## Applications

- Hematology diagnostics
- Automated laboratory analysis
- Medical image classification
- Clinical decision support systems
- Disease detection and monitoring

---

## Author

Karnati Lalith Teja  

---

## License

This project is developed for educational and research purposes.
