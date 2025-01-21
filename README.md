# Plant Pathology Analysis Using CNN 🌿🧬

## Overview  
This project focuses on classifying plant diseases using a **convolutional neural network (CNN)**. The dataset includes plant images labeled into four categories: **healthy**, **multiple diseases**, **rust**, and **scab**. The goal is to build a robust multi-class classification model to support agricultural health monitoring.

---

## Key Highlights  
- **Dataset**: [Plant Pathology 2020](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data) containing labeled plant images.  
- **Techniques**:  
  - **Data Preprocessing**: Applied image normalization, augmentation (rotations, flips, shifts, zoom), and target encoding.  
  - **Model Architecture**: Designed a CNN with:  
    - Three convolutional layers  
    - Batch normalization and max-pooling layers  
    - Dense layers for final classification  
  - **Dataset Splitting**: Divided into training (80%) and validation (20%) sets, stratified by class labels.

---

## Results  
- Achieved effective categorization of plant health conditions.  
- Conducted histogram analysis of label distribution to ensure balance and model robustness.  

---

## Features  
- **Data Augmentation**: Enhanced generalization through real-time transformations.  
- **Visualization**: Displayed sample and augmented images to analyze dataset diversity.  
- **Model**: Built using **TensorFlow/Keras**, optimized with Adam optimizer and categorical crossentropy loss.  

---

## Future Scope  
- Extend the model to handle a broader range of plant diseases.  
- Deploy the model for real-time agricultural applications to assist farmers and agricultural professionals.

---

Feel free to explore the repository and contribute to improving the model's performance and applicability! 🌱
