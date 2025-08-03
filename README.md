
# 🦠 COVID-19 Detection from Chest X-Rays using CNN

This project uses deep learning techniques to detect COVID-19 from chest X-ray images. Built using **Convolutional Neural Networks (CNNs)**, it automates the classification of X-ray scans as either COVID-positive or normal, supporting faster medical triage during pandemic conditions.

---

## 📁 Dataset

The dataset used in this project is available here:  
🔗 [Download from Dropbox](https://www.dropbox.com/scl/fi/8jafvmu9s23e3bpmaou3c/CovidDataset-20200427T133042Z-001.zip?dl=0&e=1&rlkey=p1slfgi51d7cmi5161ixvicmq)


---

## 🧪 Technologies Used

- **Language**: Python 3.9  
- **Platform**: Google Colab  
- **Libraries**:  
  - TensorFlow / Keras  
  - NumPy  
  - Matplotlib  

---

## 🧠 Model Architecture

The CNN model includes:
- `Conv2D` layers for feature extraction
- `MaxPooling2D` to reduce spatial dimensions
- `Flatten` layer to convert to 1D
- `Dense` layers for classification
- `ReLU`, `Softmax` or `Sigmoid` activations
- Regularization to avoid overfitting
- `Adam` optimizer for weight updates
- `ImageDataGenerator` for image augmentation
- `ModelCheckpoint` to save the best model

---

