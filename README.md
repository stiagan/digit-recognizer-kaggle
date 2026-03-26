#  Handwritten Digit Recognition using CNN

##  Overview
This project implements a Convolutional Neural Network (CNN) 
to classify handwritten digits (0–9) from the MNIST dataset.

The dataset is from the Kaggle competition:
Digit Recognizer.

##  Dataset
- 42,000 training images
- 28×28 grayscale pixels
- 10 output classes (0–9)

##  Techniques Used
- Convolutional Neural Networks (CNN)
- Batch Normalization
- Dropout Regularization
- Data Augmentation
- Early Stopping
- Learning Rate Scheduling
- Confusion Matrix & Error Analysis

##  Model Architecture
- Conv2D (32 filters)
- BatchNormalization
- MaxPooling
- Conv2D (64 filters)
- BatchNormalization
- Dense (128 units)
- Dropout (0.3)
- Softmax Output Layer

##  Results
- Model Accuracy: 0.99471
- Robust generalization using augmentation

##  How to Run

1. Clone repository:
   git clone https://github.com/stiagan/digit-recognizer-kaggle.git

2. Install dependencies:
   pip install -r requirements.txt

3. Run notebook.
