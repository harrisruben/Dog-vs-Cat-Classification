from pathlib import Path

# 🐶🐱 Dog vs Cat Image Classification

This is my ML project where I built and trained a **Convolutional Neural Network (CNN)** to classify whether an image is of a **Dog** or a **Cat**.  
I used the **Microsoft Cats vs Dogs dataset** from Kaggle.

## 📂 Dataset
- Dataset used: [Cats vs Dogs Dataset (Kaggle)](https://www.kaggle.com/datasets/shaunthesheep/microsoft-catsvsdogs-dataset?select=PetImages)  
- Contains around **25,000 images** of dogs and cats.

## ⚙️ Tech Stack
- Python 🐍  
- TensorFlow / Keras  
- NumPy, Pandas, Matplotlib, Seaborn  
- Jupyter Notebook  

## 📒 Project Files
- `Dog_vs_Cat.ipynb` → Model building and training notebook  
- `testing_Model.ipynb` → Testing and predictions notebook  
- `Dog-vs-Cat_model_of_HR.h5` → Trained CNN model  
- `README.md` → Project documentation (this file)  

## 🧠 Model Info
- Architecture: Convolutional Neural Network (CNN)  
- Layers: Convolution, Pooling, Flatten, Dense  
- Optimizer: Adam  
- Loss Function: Binary Crossentropy  
- Accuracy Achieved: ~**85–90%** (depending on training)  

## 🚀 How to Run
1. Clone this repo  
   ```bash
   git clone https://github.com/<your-username>/Dog-vs-Cat-Classification.git
   cd Dog-vs-Cat-Classification
