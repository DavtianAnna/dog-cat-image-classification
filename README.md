# 🐶🐱 Dog vs Cat Image Classification

This repository contains a deep learning model that classifies images as either a **dog** or a **cat**.  
The project is implemented using **Python**, **Keras**, and standard ML utilities.

---

## ✨ Features
- **CNN Model**: Robust architecture for feature extraction and classification.  
- **Data Preprocessing**: Grayscale conversion + resizing to **48x48**.  
- **Performance**: Achieved **~90% validation accuracy**.  

---

## 📂 Dataset
- Dataset includes labeled images of **dogs** and **cats**.  
- Preprocessed to **grayscale (48x48)**.  
- Split into **training** and **testing** sets.  

---

## 🏗️ Model Architecture
- **Convolutional layers** with ReLU activation  
- **MaxPooling** for feature reduction  
- **BatchNormalization** for training stability  
- **Dense layers** with **Sigmoid** output (binary classification: Dog / Cat)  

---

## ⚙️ Training
- **Loss**: `binary_crossentropy`  
- **Optimizer**: `Adam`  
- **Metrics**: `accuracy`  

---

## 🚀 Results
- Validation Accuracy: **~90%**  
- Model can generalize well to unseen images  

---

## 🛠️ Getting Started

### Installation
```bash
git clone https://github.com/<username>/dog-cat-image-classification.git
cd dog-cat-image-classification
pip install -r requirements.txt
