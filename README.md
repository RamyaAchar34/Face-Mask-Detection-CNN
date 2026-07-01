# 😷 Face Mask Detection using Convolutional Neural Network (CNN)

## 📌 Overview

This project implements a **Convolutional Neural Network (CNN)** to classify facial images into two categories: **With Mask** and **Without Mask**. The model is developed using TensorFlow and Keras, demonstrating the complete workflow of image preprocessing, model training, evaluation, and prediction.

---

## 🎯 Objective

The objective of this project is to build a deep learning model capable of accurately detecting whether a person is wearing a face mask. Such models can assist in automated public safety monitoring and real-time surveillance applications.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

The dataset consists of facial images categorized into two classes:

- 😷 With Mask
- 😀 Without Mask

Images were resized, converted into NumPy arrays, normalized, and split into training and testing datasets before training the CNN model.

---

## 🔄 Project Workflow

- Import required libraries
- Load and preprocess image dataset
- Resize and normalize images
- Encode class labels
- Split data into training and testing sets
- Build a Convolutional Neural Network (CNN)
- Train the model
- Evaluate model performance
- Predict image classes
- Save the trained model

---

## 🧠 CNN Architecture

The model includes:

- Convolutional Layers
- ReLU Activation Function
- Max Pooling Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Softmax Output Layer

---

## 📈 Model Training

The CNN model was trained for **10 epochs** using the Adam optimizer and Sparse Categorical Crossentropy loss function.

### Training Progress

![Training Results](Images/training_results.png)

---

## 📊 Model Performance

The trained model achieved excellent classification performance on the test dataset.

### Classification Report

| Metric | Score |
|--------|------:|
| Accuracy | **98.58%** |
| Precision | **99%** |
| Recall | **99%** |
| F1-Score | **99%** |

### Classification Results

![Classification Report](Images/model_results.png)

---

## 📁 Project Structure

```
Face-Mask-Detection-CNN/
│
├── Images/
│   ├── training_results.png
│   └── model_results.png
│
├── Face_Mask_Detection_CNN.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📌 Future Enhancements

- Increase dataset size for improved generalization.
- Apply data augmentation techniques.
- Use Transfer Learning models such as MobileNetV2 or ResNet50.
- Deploy the model using Streamlit or Flask.
- Enable real-time face mask detection using a webcam.

---

## 👩‍💻 Author

**Ramya Achar**

Aspiring Data Scientist | Machine Learning & Deep Learning Enthusiast

---

⭐ **If you found this project helpful, consider giving it a star!**
- **LinkedIn:** www.linkedin.com/in/ramya-achar-916b8b327
- **GitHub:** https://github.com/RamyaAchar34
