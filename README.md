# Aniaml_classificatiion
In this we actually do is we used neural network model to classify the different classes in the dataset .

# 🐶🐱🐴🐄 Animal Image Classification using CNN

This project is an *image classification model* built using *TensorFlow/Keras* to classify animal images into *15 different classes* (e.g., horse, dog, cat, cow, etc.).  
The dataset is organized in folders, and a Convolutional Neural Network (CNN) is trained to predict the correct class for a given image.

---

> 📎 *Note:* The dataset was split into train/ and test/ folders using a Python script (train-test split) from a single dataset folder.

---

## 🧠 *Model Architecture*

The model uses an improved CNN structure with *Batch Normalization, **Dropout, and **Global Average Pooling* to improve performance and reduce overfitting:

- 3 × Conv2D blocks (32, 64, 128 filters)  
- BatchNormalization after each conv layer  
- Dropout for regularization  
- we use Flatten  layer
- Fully connected dense layer  
- Output softmax layer for 15 classes

---

## ⚡ *Technologies Used*

- 🧠 *TensorFlow / Keras* – Model building & training  
- 🐍 *Python 3*  
- 🖼 *ImageDataGenerator* for data loading & augmentation  
- 📊 Matplotlib / Seaborn for visualization (optional)

---
