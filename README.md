# 🥦 Vegetable Image Classifier CNN 

![Vegetable Banner](Vegetables.jpg)

**A Convolutional Neural Network (CNN) for classifying grayscale vegetable images into multiple classes at two resolutions (23x23 and 101x101).**

---

## 🧩 Features

- 🥕 **Multi-Resolution Classification**: Train and evaluate models on both 23x23 and 101x101 images.  
- 📊 **Performance Comparison**: Compare accuracy between different resolutions.  
- 🧪 **Model Training & Evaluation**: Includes training pipelines, validation, and metrics.  
- 📈 **Visualization**: Training and validation accuracy/loss plots for analysis.  

---

## 📚 Dataset

- **Custom Vegetable Dataset**  
  - Grayscale images of 11 vegetable classes.  
  - Two resolutions: 23x23 and 101x101 pixels.  

---

## 🏗 Model Architecture

**Convolutional Neural Network (CNN)** with:  

- **Convolutional Layers**: Extract spatial features from images.  
- **Max-Pooling Layers**: Reduce spatial dimensions and retain important features.  
- **Fully Connected Layers**: Map extracted features to class probabilities.  
- **Activation Functions**: ReLU for hidden layers, softmax for output layer.  

Optimized using KerasTuner for best accuracy on both resolutions.

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/4ndrrw/Vegetable-Image-Classifier-CNN.git
cd Vegetable-Image-Classifier-CNN

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

---

## 📈 Results

### 23x23 Resolution Model
![23x23 Model Training](tuned_23_model.png)

### 101x101 Resolution Model
![101x101 Model Training](tuned_101_model.png)

*The 101x101 model achieved higher accuracy due to increased input resolution.*

---

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?logo=Visual%20Studio%20Code&logoColor=white)

---

## 🤝 Contributing

1. Fork the repository.  
2. Create a new branch (`git checkout -b feature-branch`).  
3. Commit your changes (`git commit -am 'Add new feature'`).  
4. Push to the branch (`git push origin feature-branch`).  
5. Open a Pull Request.

---
