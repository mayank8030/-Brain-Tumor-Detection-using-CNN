# 🧠 Brain Tumor Detection using Convolutional Neural Network (CNN)

## 📌 Project Overview
This project implements a **Convolutional Neural Network (CNN)** to classify brain MRI scans into different tumor categories. The model is trained on a publicly available MRI dataset and is capable of identifying different types of brain tumors with high accuracy. The project demonstrates the complete deep learning workflow, including data preprocessing, model training, evaluation, and prediction.

---

## 📂 Dataset
**Dataset Name:** Brain Tumor MRI Dataset
**Source:** Kaggle
**Dataset Link:** https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

### Classes
* 🟢 Glioma
* 🔵 Meningioma
* 🟡 Pituitary
* ⚪ No Tumor

The dataset contains thousands of labeled MRI images distributed across these four classes.

---

## 🏗️ Model Architecture
A **Custom Convolutional Neural Network (CNN)** was developed for this project.

### Architecture
* Conv2D (32 Filters)
* MaxPooling2D
* Conv2D (64 Filters)
* MaxPooling2D
* Flatten
* Dense (128 Neurons)
* Dropout (0.5)
* Output Layer (Softmax)

### Techniques Used
* Image Rescaling
* Data Augmentation
* Dropout Regularization
* Early Stopping
* Adam Optimizer
* Categorical Crossentropy Loss

---

## 📊 Results
| Metric              | Value     |
| ------------------- | --------- |
| Training Accuracy   | **97.2%** |
| Validation Accuracy | **93.6%** |
| Test Accuracy       | **97.9%** |

---

## 🛠️ Tech Stack
* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 📁 Project Structure
```
Brain-Tumor-Detection-CNN/
│
├── brain_tumor_detection.ipynb
├── requirements.txt
├── README.md
├── brain_tumor_model.keras
└── images/
    ├── accuracy.png
    ├── loss.png
    └── prediction.png
```

---

## ⚙️ Installation & How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/Brain-Tumor-Detection-CNN.git
cd Brain-Tumor-Detection-CNN
```

### 2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate   # Mac/Linux
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the notebook
```bash
jupyter notebook brain_tumor_detection.ipynb
```

### 5. Predict on a new image
Load the saved model (`brain_tumor_model.keras`) inside the notebook and pass a new MRI image to get the predicted tumor class.

---

## 📦 requirements.txt
```
tensorflow
numpy
pandas
opencv-python
matplotlib
scikit-learn
jupyter
```

---

## 📈 Features
* MRI Image Classification
* Brain Tumor Detection
* Data Augmentation
* Custom CNN Architecture
* Early Stopping
* Model Evaluation
* Single Image Prediction
* Model Saving

---

## 🔮 Future Improvements
* Implement Transfer Learning (ResNet50, EfficientNet)
* Deploy using Streamlit or Flask
* Hyperparameter Tuning
* Real-time MRI Image Prediction
* Model Explainability using Grad-CAM

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author
**Mayank Singh**

If you found this project helpful, consider giving it a ⭐ on GitHub.
