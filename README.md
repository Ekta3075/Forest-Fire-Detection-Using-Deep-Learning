# 🌲 Forest Fire Detection Using Deep Learning 🔥

This project applies deep learning techniques to classify forest images into **fire** or **no fire** categories. It leverages Convolutional Neural Networks (CNNs) for image classification, using a real-world dataset of forest scenarios.

---

## 📌 Project Goal

To detect forest fires early by classifying images using a trained deep learning model, enabling quick and automated decision-making in forest monitoring systems.

---

## 🧾 Dataset

- **Source**: https://www.kaggle.com/datasets/elmadafri/the-wildfire-dataset
- **Classes**:
  - `Fire`
  - `No Fire`
- **Format**: JPEG images categorized in folders (`train`, `test`)

---

## 🧠 Model Architecture

The model is built using TensorFlow's Keras API with a `Sequential` CNN architecture. Some of the core components:

- Convolutional Layers (`Conv2D`)
- Pooling Layers (`MaxPooling2D`)
- Flatten + Dense Layers
- Dropout for regularization

> 🧪 **Optimizer Used**: Adam  
> 🔧 **Learning Rate**: 0.0001   
> 📊 **Evaluation Metric**: Accuracy

---

## 🔍 Image Preprocessing

- Rescaling and Augmentation done using `ImageDataGenerator`
- Target Size: Typically (150x150) or similar for input images
- Data split into training and validation sets using directory structure

---

## 📈 Results & Evaluation

> *Metrics were printed but not clearly stored in variables — please update if final values are known.*

- Training/Validation accuracy shown via plots
- Sample predictions include both `correct` and `incorrect` classifications
- Model saved for reuse (`.h5` format)
