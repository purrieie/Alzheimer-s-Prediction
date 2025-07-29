# Alzheimers-Prediction
Hybrid model for detecting Alzheimer's disease; CNN (MobileNetV2) for feature extraction, SVM for classification. 

This project uses the Alzheimer's disease dataset from Kaggle which comprises of MRI scan images, divided into four categories: MildDemented, ModerateDemented, NonDemented and VeryMildDemented.

Preprocessing:
resizing images to 64x64, 
scaling pixel values to fall within [0,1],
80:20 train:test split
one hot encoding each class label.

used SMOTE for oversampling minority classes and hence fixing class imbalance. 

Results:
90%  validation accuracy
