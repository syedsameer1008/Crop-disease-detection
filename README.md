# 🌿 Plant Disease Classification using CNN

## 📌 Project Overview

This project focuses on building a **Convolutional Neural Network (CNN)** model to classify plant leaf diseases using image data from the **PlantVillage dataset**. The model is implemented using **TensorFlow (Keras API)** and trained to recognize multiple disease categories from plant leaf images.

The objective of this project is to develop an automated system that can assist farmers and agricultural experts in early disease detection using deep learning techniques.

---

## 🚀 Features

* Image preprocessing and augmentation
* CNN-based deep learning model
* Multi-class disease classification
* Training and validation split
* Performance visualization using accuracy and loss graphs

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow / Keras** – Deep Learning framework
* **OpenCV** – Image processing
* **scikit-learn** – Dataset splitting and preprocessing utilities
* NumPy & Matplotlib – Numerical operations and visualization

---

## 📂 Dataset

The dataset used in this project is the **PlantVillage dataset**, which contains labeled images of healthy and diseased plant leaves.

### Dataset Structure:

```
dataset/
│
└── plantvillage/
    ├── class_1/
    ├── class_2/
    ├── ...
```

Each folder represents a disease class.

---

## 🧠 Model Architecture

The CNN model consists of:

* Convolutional layers (Conv2D)
* MaxPooling layers
* Flatten layer
* Fully connected (Dense) layers
* Dropout layer (for regularization)
* Softmax activation (for multi-class classification)

### Input Configuration:

* Image Size: **224 × 224**
* Batch Size: **32**
* Epochs: **10**
* Loss Function: `categorical_crossentropy`
* Optimizer: `adam`

---

## 🔄 Data Preprocessing

The project uses `ImageDataGenerator` for:

* Rescaling pixel values
* Rotation
* Horizontal flipping
* Zoom augmentation
* Training-validation splitting

This helps improve model generalization and prevent overfitting.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone <repository-url>
cd <project-folder>
```

### 2️⃣ Install Dependencies

```bash
pip install tensorflow numpy matplotlib opencv-python scikit-learn
```

### 3️⃣ Update Dataset Path

Modify the dataset directory in the notebook:

```python
DATA_DIR = 'dataset/plantvillage/'
```

### 4️⃣ Run the Notebook

Open the Jupyter Notebook:

```bash
jupyter notebook capestone_project_91.ipynb
```

Run all cells to train and evaluate the model.

---

## 📊 Output

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss
* Disease class predictions

Graphs are plotted using Matplotlib to visualize model performance.

---

## 🎯 Applications

* Smart agriculture systems
* Automated crop monitoring
* Mobile-based plant disease detection
* Precision farming solutions

---

## 🔮 Future Improvements

* Increase dataset size for better accuracy
* Implement Transfer Learning (e.g., pre-trained models)
* Deploy as a web or mobile application
* Integrate real-time camera-based detection
* Improve model tuning and hyperparameter optimization

---

## 👨‍💻 Author

Developed as part of a Capstone Project on Deep Learning for Agricultural Image Classification.

---
