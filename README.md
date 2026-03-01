🧠 Convolutional Neural Network (CNN) Feature Extraction and Classification

NHS Project

📌 Project Overview

This project focuses on using Convolutional Neural Networks (CNNs) for feature extraction and image classification in a healthcare context. The work was carried out as part of a project for the National Health Service (NHS), exploring how deep learning models can extract meaningful visual features from medical images to support classification tasks.

The project evaluates multiple pre-trained CNN architectures and compares their effectiveness as feature extractors for downstream classification.

🎯 Objectives

To investigate the performance of pre-trained CNN models for feature extraction

To compare different architectures (VGG, ResNet variants)

To analyze the impact of data augmentation and dimensionality reduction (PCA)

To support accurate and reliable image classification in a healthcare setting

🧪 Methodology

Model Selection
Used well-known CNN architectures such as:

VGG16 / VGG19

ResNet50 / ResNet152

Feature Extraction

Removed final classification layers

Extracted deep feature vectors from convolutional layers

Preprocessing & Augmentation

Image normalization

Data augmentation to improve generalization

Dimensionality Reduction

Applied Principal Component Analysis (PCA) to reduce feature dimensionality

Classification & Evaluation

Used extracted features for classification

Compared performance across models and configurations

📊 Key Outcomes

Demonstrated how different CNN architectures affect feature quality

Showed improvements in classification performance using data augmentation

Highlighted the trade-off between feature dimensionality and accuracy using PCA

🛠 Technologies Used

Python

TensorFlow / Keras

NumPy, OpenCV, Matplotlib

Jupyter Notebook

🏥 Healthcare Context

This work was conducted for an NHS-related project, aiming to explore how deep learning techniques can assist in medical image analysis and decision support systems.

⚠️ Note: Due to data privacy and confidentiality, datasets and sensitive details are not included in this repository.

🚀 Future Improvements

Integration with clinical workflows

Experimentation with Vision Transformers (ViTs)

Automated hyperparameter optimization

Deployment as a lightweight inference service
