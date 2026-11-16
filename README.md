# Satellite Image Classification 🛰️

A deep learning computer vision project that classifies remote sensing satellite imagery into four distinct land-cover and weather categories: **Cloudy**, **Desert**, **Green Area**, and **Water**.

## 📊 Dataset
* **Source:** [Satellite Image Classification Dataset (RSI-CB256)](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification) on Kaggle
* **Total Images:** ~5,631 satellite and Google Maps snapshot images (256×256 resolution)
* **Classes (4):** `Cloudy`, `Desert`, `Green_Area`, `Water`

## 🛠️ Tech Stack & Approach
* **Language:** Python
* **Libraries:** TensorFlow / Keras (or PyTorch), NumPy, Pandas, Matplotlib, Scikit-learn
* **Methodology:** 
  * Image preprocessing, normalization, and train/validation splitting
  * Data augmentation (rotation, flipping, zooming) to improve generalization
  * Model architecture: [e.g., Custom CNN / Transfer Learning with VGG19 / ResNet50 / MobileNetV2]

## 📈 Results
* **Validation / Test Accuracy:** [e.g., 96.5%]
* Evaluated using accuracy/loss curves, confusion matrix, and classification report across all 4 classes.

## 🚀 Run the Notebook
Click the **"Open in Colab"** badge at the top of `AI project.ipynb` to run the code directly in your browser.
