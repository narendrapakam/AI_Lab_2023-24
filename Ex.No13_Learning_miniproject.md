
# Ex.No: 13 
Brain Tumor Detection Using Deep Learning
### DATE: 13/05/2025                                                                           
### REGISTER NUMBER : 212222060171
### AIM: 
To design and implement a deep learning-based system for detecting brain tumors in MRI scans, with the goal of accurately classifying tumor types (glioma, meningioma, pituitary) and enabling early diagnosis to support medical decision-making.###  Algorithm:
##
# ALGORITHM:
Step1:Data Collection
  Gather brain MRI scans from public datasets (e.g., Figshare, BraTS)
  Include tumor types: Glioma, Meningioma, Pituitary, No Tumor

Step 2:Data Preprocessing
  Resize images to a fixed dimension (e.g., 224x224)
  Normalize pixel values (0-1 range)
  Apply data augmentation (rotation, flipping, zoom)

Step 3:Feature Selection
   Use CNN-based architectures (ResNet, VGG, EfficientNet)
   Extract deep features from MRI scans

Step 4:Label Definition
   Convolutional Neural Network (CNN)
   Transfer Learning (ResNet50, VGG16)
   Custom CNN Architecture

Step 5:Model Selection
   Split data into Train (80%), Validation (10%), Test (10%)
   Use Adam optimizer with learning rate scheduling
   Apply Early Stopping to prevent overfitting

Step 6:Model Training
   Accuracy, Precision, Recall, F1-Score
   Confusion Matrix
   ROC-AUC Curve
