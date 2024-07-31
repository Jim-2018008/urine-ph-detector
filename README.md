# Urine pH Detection Web Application

## Project Overview

This project focuses on detecting urine pH using a web application that captures images of pH strips. By analyzing the pH level obtained from these images, I can determine the concentration of urea in the urine and subsequently calculate the Blood Urea Nitrogen (BUN) level using the formula:

BUN (mg/dL)=Urea concentration (mmol/L)×2.8

## Problem Definition

The aim is to provide an accessible and non-invasive method for monitoring Chronic Kidney Disease (CKD) by detecting urine pH levels through a web application. This method offers a simpler alternative to traditional invasive techniques.

## Project Goals

1. **Optimize Dataset Utilization**: Efficiently use the provided dataset for training and testing.
2. **Develop a Web App**: Create a user-friendly web application for pH detection.
3. **Assist Patients**: Help patients easily detect CKD through the web app.

## Literature Review

The paper "Machine Learning-Based pH Color Recognition for Monitoring Chronic Kidney Disease" explores predicting pH values using RGB profile data from pH test strips. This approach aims to provide a less invasive monitoring method. The study faces challenges due to limited datasets and the presence of outliers.

## Methodology

I evaluated three machine learning models on the dataset: KNN, SVM, and Neural Networks. Additionally, I attempted to improve accuracy by employing a Random Forest model.

### Steps:

1. **Data Import and Preprocessing**: Imported the pH dataset and mapped it to RGB values. Conducted exploratory data analysis (EDA) and performed train-test split.
2. **Image Processing**: Used OpenCV for image processing and averaging RGB values.
3. **Model Training**: Utilized KNN, SVM, and Neural Network models for pH prediction.
4. **Web App Development**: Integrated all components into a user-friendly web application.

## Model Evaluation

- **KNN Model**:
  - Initial accuracy: 71.75%
  - Improved accuracy: 82% after adjusting test-train percentage

- **SVM Model**:
  - Accuracy: 69.4%, consistent with the paper

- **Neural Network Model**:
  - Accuracy decreased with increasing epochs

- **Random Forest Model**:
  - Additional attempts to enhance accuracy

### Confusion Matrices

- **KNN**: n_neighbors=10
- **SVM**: Poly Kernel
- **Random Forest**: n_estimators=16, max_depth=22

## Project Timeline

- **Week 1**: Explored datasets and reviewed the literature.
- **Week 2**: Gathered information on additional datasets.
- **Week 3**: Initiated data processing and model training.
- **Week 4**: Improved model accuracy.
- **Week 5**: Developed the web app and conducted beta testing.

## Results

The project achieved comparable results to the referenced paper, with notable improvements in KNN accuracy through iterative testing and parameter adjustments.

## Questions?

If you have any questions or need further information, feel free to reach out.

---

**Thank you for your interest in the project!**

---
