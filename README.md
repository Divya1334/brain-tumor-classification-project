## 🧠 Brain Tumor Classification Using CNN & Transfer Learning
📌 Project Overview

This project focuses on brain tumor classification using deep learning and computer vision.

A Convolutional Neural Network (CNN) is trained to analyze brain MRI images and classify them into different categories. The project also demonstrates the use of transfer learning with a pretrained CNN model.

The model classifies MRI images into four classes:

Glioma
Meningioma
Pituitary
No Tumor

🎯 Objective

The main objective of this project is to build an image classification model that can:

-Process brain MRI images

-Learn important image features

-Classify MRI images into the appropriate category

-Evaluate model performance using training and validation data

-Predict the class of a new MRI image

Note: This is an educational machine-learning project and is not intended for medical diagnosis.

🧠 Classes

Class

Description

Glioma :
MRI images belonging to the glioma category

Meningioma :
MRI images belonging to the meningioma category

Pituitary :
MRI images belonging to the pituitary category

No Tumor :
MRI images without a tumor according to the dataset labels

🛠️ Technologies Used

Python
TensorFlow
Keras
NumPy
Matplotlib
Computer Vision
Convolutional Neural Networks (CNN)
Transfer Learning

🧩 Deep Learning Approach

CNN

CNNs are particularly useful for image-based tasks because they can automatically learn visual features such as:
Edges
 
Textures
 
Shapes
 
Complex Features
 
Tumor-related Patterns

Transfer Learning

A pretrained CNN model is used as the starting point instead of training the entire network from scratch.
The pretrained model provides previously learned visual features, which can then be adapted to the brain MRI classification task.
Two approaches are used:

Feature Extraction

Pretrained layers are frozen.
A new classification layer is trained.

Fine-Tuning

Some pretrained layers are unfrozen.
These layers are trained with a small learning rate to adapt the model to the new dataset.

📊 Model Evaluation

The model can be evaluated using:

Training Accuracy

Validation Accuracy

Training Loss

Validation Loss

Training and validation curves can also be used to identify potential overfitting or underfitting.

🔮 Prediction

After training, a new MRI image can be passed to the model:

MRI Image
    
Preprocessing
    
Trained CNN
    
Class Probabilities
    
Highest Probability
    
Predicted Class

Example:

Glioma       → 0.02

Meningioma   → 0.94

No Tumor     → 0.01

Pituitary    → 0.03

Prediction → Meningioma

The complete MRI dataset is not included in this repository because of its large size.
The dataset was used locally for model training, validation, and testing.

🚀 Future Improvements

Experiment with different pretrained models such as ResNet, VGG, EfficientNet, or MobileNet
Improve data augmentation
Compare feature extraction and fine-tuning performance
Use a confusion matrix for detailed class-wise analysis
Build a simple web application for image prediction.

👩‍💻 Author

Divya K

BTech Graduate | AI/ML Learner

Interested in Artificial Intelligence, Machine Learning, Deep Learning, and Computer Vision.
