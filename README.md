Plant Pathology Analysis Using CNN
Overview
This project focuses on classifying plant diseases using a convolutional neural network (CNN). The dataset includes plant images labeled into four categories: healthy, multiple diseases, rust, and scab. The aim is to create a robust multi-class classification model to support agricultural health monitoring.

Key Highlights
Dataset: Plant Pathology 2020 containing labeled images.
Techniques:
Data Preprocessing: Image normalization, augmentation (rotations, flips, shifts, and zoom), and target encoding.
Model Architecture: A CNN with three convolutional layers, batch normalization, max-pooling, and dense layers for classification.
Splitting: Dataset split into training (80%) and validation (20%) sets, stratified by class labels.
Results:
Achieved effective categorization of plant health conditions.
Histogram analysis of label distribution to ensure balance and model robustness.
Features
Data Augmentation: Enhanced generalization through real-time transformations.
Visualization: Displayed sample and augmented images to understand dataset diversity.
Model: CNN built using TensorFlow/Keras, optimized with Adam optimizer and categorical crossentropy loss.
Future Scope
Extend the model to handle more plant diseases.
Deploy the model for real-time agricultural applications.
