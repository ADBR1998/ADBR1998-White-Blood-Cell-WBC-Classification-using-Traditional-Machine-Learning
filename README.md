# ADBR1998-White-Blood-Cell-WBC-Classification-using-Traditional-Machine-Learning
This project focuses on classifying White Blood Cells (WBCs) into different types using traditional machine learning techniques. The goal was to apply image processing and classical ML algorithms on biomedical image data for use in diagnostic applications.
 **Objectives**
-Preprocess WBC images for enhanced clarity and consistency
-Extract features from each cell image (shape, color, texture)
-Train and evaluate classical ML models for accurate WBC classification

**Dataset**
The dataset consists of labeled WBC images from microscopic blood smear slides.

Each image corresponds to a specific WBC type such as:
Neutrophils
Lymphocytes
Monocytes
Eosinophils
Basophils

****Techniques Used****
**Image Preprocessing**
Resizing and normalization
Grayscale conversion
Thresholding and segmentation
Morphological operations (e.g., erosion, dilation)

**Feature Extraction**
Color features: Mean and standard deviation of RGB or HSV channels
Shape features: Area, perimeter, circularity
Texture features: Haralick features from the GLCM (Gray-Level Co-occurrence Matrix)

**Classification Algorithms**
Logistic Regression
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)

**Evaluation Metrics**
Accuracy
Precision / Recall / F1-Score
Confusion Matrix
