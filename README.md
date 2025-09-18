# 🌿 Plant Disease Detection

This project detects plant leaf diseases using **Machine Learning (SVM, Random Forest)** and **Deep Learning (Custom CNN)**.  
It also includes a **Gradio/Streamlit app** for easy predictions from uploaded leaf images.

---

## 🚀 Features
- Preprocessing: Image resizing, normalization, label encoding
- Models:
  - Support Vector Machine (SVM)
  - Random Forest
  - Convolutional Neural Network (CNN)
- User Interfaces:
  - Gradio Web UI
  - Streamlit App
- Training & Evaluation scripts
- Visualization of dataset histograms and training curves

---

## ⚙️ Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/Swarna-N-T/plant-disease-detection.git
   cd plant-disease-detection

2. Install dependencies:
   ```bash
    pip install -r requirements.txt

3. Train models:
   ```bash
    python src/train.py

4. Run Gradio app:
   ```bash
    python app/gradio_app.py

5. Run Streamlit app:
   ```bash
    streamlit run app/streamlit_app.py

---

## 📌 Dataset
- The project uses the [PlantVillage dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1) from Kaggle
---

## 📊 Results
- CNN Accuracy: ~89% (can be improved with data augmentation / transfer learning)
- SVM & Random Forest: Lower than CNN
- Confusion matrix and training curves are available in results/

---
improved version

