# 🧠 Skin Cancer Detection using CNN

## 📌 Project Overview

This project focuses on building a **Convolutional Neural Network (CNN)** to classify skin lesion images as:

* **Benign (Non-Cancerous)**
* **Malignant (Cancerous)**

The goal is to assist in early detection of skin cancer using deep learning techniques.

---

## 🚀 Features

* Image preprocessing and augmentation
* Custom CNN architecture (built from scratch)
* Model training with callbacks (EarlyStopping & ReduceLROnPlateau)
* Performance evaluation using:

  * Accuracy
  * Classification Report
  * Confusion Matrix
* Prediction on new images

---

## 📂 Dataset

The dataset contains labeled images of skin lesions divided into:

* `train/`
* `test/`

Each folder contains two classes:

* `benign`
* `malignant`

---

## 🛠️ Technologies Used

* Python 🐍
* TensorFlow / Keras
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🧪 Data Preprocessing

* Resizing images to **224x224**
* Normalization (`rescale=1./255`)
* Data augmentation:

  * Rotation
  * Zoom
  * Horizontal flipping

---

## 🧠 Model Architecture

The CNN consists of:

* Convolutional Layers (feature extraction)
* MaxPooling Layers (downsampling)
* Batch Normalization (stabilization)
* Global Average Pooling
* Fully Connected Dense Layers
* Dropout (to prevent overfitting)
* Sigmoid activation for binary classification

---

## ⚙️ Training Details

* Optimizer: **Adam**
* Loss Function: **Binary Crossentropy**
* Batch Size: **32**
* Epochs: **30**
* Callbacks:

  * EarlyStopping
  * ReduceLROnPlateau

---

## 📊 Model Evaluation

The model is evaluated using:

* Accuracy Score
* Precision, Recall, F1-score
* Confusion Matrix visualization

---

## 📈 Results

* Model achieved moderate accuracy using a custom CNN
* Performance can be further improved using transfer learning (e.g., EfficientNet, ResNet)

---

## 🔍 Prediction Example

The model can predict whether a given skin image is:

* **Benign**
* **Malignant**

---

## ⚠️ Limitations

* Accuracy is limited due to training CNN from scratch
* Medical datasets require large-scale data for better performance

---

## 🚀 Future Improvements

* Implement Transfer Learning (EfficientNet, ResNet)
* Improve dataset quality and balance
* Hyperparameter tuning
* Deploy as a web application (Streamlit/Flask)

---



## ⭐ If you like this project

Give it a ⭐ on GitHub!
