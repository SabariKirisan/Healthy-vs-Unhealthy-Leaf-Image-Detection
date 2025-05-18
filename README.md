# Anthracnose Disease Analysis Using Deep Learning

This project focuses on detecting **Anthracnose disease** in plant leaves using a deep learning approach. It employs **InceptionV3**, a pre-trained Convolutional Neural Network (CNN), for binary image classification—distinguishing between **healthy** and **unhealthy (anthracnose-infected)** leaves. The workflow includes data preprocessing, model training, evaluation, visualization, and export to TensorFlow Lite for deployment.

---

## 🧠 Model Overview

- **Model Architecture**: InceptionV3 (pre-trained on ImageNet)
- **Input Image Size**: 240x240
- **Number of Classes**: 2 (`healthy`, `unhealthy`)
- **Frameworks Used**: TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn
- **Export Format**: `.h5` and `.tflite`

---

## 📂 Project Dataset

    dataset/
      - training/
          -healthy/
          -unhealthy/
      - validation/
          - healthy/
          - unhealthy/
      - testing/
          - healthy/
          - unhealthy/

---

## Run the Main Script
python main.py

---

## 📊 Features

- Real-time image preprocessing and augmentation
- Model training using transfer learning (InceptionV3)
- Confusion matrix and classification report
- ROC curve for each class
- Accuracy, sensitivity, and specificity calculations
- Export predictions and metrics to .csv and .xlsx
- Convert model to TensorFlow Lite for deployment
- Visual output of sample predictions

---

## 📈 Performance Metrics

- Accuracy
- Sensitivity (Recall for the positive class)
- Specificity (True Negative Rate)
- Confusion Matrix
- Classification Report
- ROC Curve and AUC

---

## 🖼️ Outputs

- Confusion matrix heatmap
- ROC curves for each class
- Predicted labels over sample test images

## 📱 Model Deployment
The trained model is converted into .tflite format, suitable for deploying on:

- Android / iOS apps
- Edge devices (e.g., Raspberry Pi)
- Embedded systems with TensorFlow Lite support
