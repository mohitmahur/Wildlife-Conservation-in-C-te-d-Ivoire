🦁 Wildlife Conservation in Côte d'Ivoire
AI Certification | WorldQuant University

This project aims to help scientists track wildlife in Côte d'Ivoire using deep learning models to classify animals in camera trap images. The workflow involves image preprocessing, fixing code issues, binary classification, and multiclass classification.

📌 Project Overview
Objective: Classify images from camera traps to identify animals.
Dataset: Images collected from Côte d'Ivoire wildlife reserves.
Tech Stack: Python, TensorFlow/PyTorch, OpenCV, Scikit-learn.
🏗️ Workflow & Jupyter Notebooks
The project follows a structured pipeline, with each step documented in separate notebooks:

1️⃣ Image Preprocessing 🖼️
Notebook: 01_image_preprocessing.ipynb

Resizing & normalizing images.
Removing noise & unwanted artifacts.
Data augmentation (rotation, flipping, etc.).
2️⃣ Fixing Code Issues 🔧
Notebook: 02_fixing_code.ipynb

Identifying & fixing coding errors.
Ensuring dataset integrity.
Verifying label consistency.
3️⃣ Binary Classification (Animal vs. No Animal) 🐾
Notebook: 03_binary_classification.ipynb

Training a CNN to classify "Animal" vs. "No Animal".
Evaluating accuracy, precision, recall, and F1-score.
4️⃣ Multiclass Classification (Identifying Animal Species) 🦓
Notebook: 04_multiclass_classification.ipynb

Expanding classification to multiple species.
Fine-tuning a pre-trained model (e.g., ResNet, EfficientNet).
Handling imbalanced classes with data augmentation.
