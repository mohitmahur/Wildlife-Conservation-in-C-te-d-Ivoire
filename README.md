# 🦁 Wildlife Conservation in Côte d'Ivoire  
**AI Certification | WorldQuant University**  

This project helps scientists track wildlife in Côte d'Ivoire by using deep learning models to classify animals in camera trap images. The workflow involves **image preprocessing, fixing code issues, binary classification, and multiclass classification** using **CNN, RNN, and Backpropagation**.  

---

## 📌 **Project Overview**  
- **🎯 Objective:** Classify images from camera traps to identify animals.  
- **📂 Dataset:** Images collected from Côte d'Ivoire wildlife reserves.  
- **🛠 Tech Stack:** Python, PyTorch, OpenCV, Scikit-learn.  

---

## 🏗️ **Workflow & Jupyter Notebooks**  
The project follows a structured pipeline, with each step documented in separate notebooks:  

### **1️⃣ Image Preprocessing 🖼️**  
📌 **Notebook:** [`01_image_preprocessing.ipynb`](notebooks/01_image_preprocessing.ipynb)  
✔️ Resizing & normalizing images.  
✔️ Removing noise & unwanted artifacts.  
✔️ Data augmentation (rotation, flipping, etc.).  

### **2️⃣ Fixing Code Issues 🔧**  
📌 **Notebook:** [`02_fixing_code.ipynb`](notebooks/02_fixing_code.ipynb)  
✔️ Identifying & fixing coding errors.  
✔️ Ensuring dataset integrity.  
✔️ Verifying label consistency.  

### **3️⃣ Binary Classification (Animal vs. No Animal) 🐾**  
📌 **Notebook:** [`03_binary_classification.ipynb`](notebooks/03_binary_classification.ipynb)  
✔️ **Model:** Convolutional Neural Network (CNN).  
✔️ **Training:** Binary classification - **"Animal" vs. "No Animal"**.  
✔️ **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score.  

### **4️⃣ Multiclass Classification (Identifying Animal Species) 🦓**  
📌 **Notebook:** [`04_multiclass_classification.ipynb`](notebooks/04_multiclass_classification.ipynb)  
✔️ **Model:** CNN + RNN (for sequential image patterns).  
✔️ **Backpropagation** to optimize the network.  
✔️ **Fine-tuning:** Transfer learning with ResNet/EfficientNet.  
✔️ **Handling imbalanced classes** with data augmentation.  

---
 
