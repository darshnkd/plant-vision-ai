# 🌿 PlantVision AI – Plant Disease Detection using EfficientNet (PyTorch)

🚀 An advanced deep learning model to detect plant diseases using leaf images. Built with **PyTorch** and powered by **EfficientNet**, this model achieves a **99.7% test accuracy** on the PlantVillage dataset. Deployed as a fast and user-friendly **Streamlit web app** on **Hugging Face Spaces**.

🔗 **Live Streamlit App**: [PlantVision AI on Hugging Face Spaces](https://huggingface.co/spaces/darshnkd/PlantVsionAI)  
📊 **Dataset**: [PlantVillage (Kaggle)](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)  
📘 **Explore the Notebook**: [Kaggle Notebook – 99.7% Accuracy](https://www.kaggle.com/code/darshnkd/plant-disease-detection-99-7-acc)


---

## 🧠 About the Project

Plant diseases significantly impact agricultural productivity and food security. PlantVision AI is an AI-driven tool designed to automatically identify diseases from plant leaf images, helping farmers and researchers in early disease detection and treatment.

### ✨ Key Features
- ✅ 99.7% test accuracy
- 🌱 Trained on over **54,000** high-quality leaf images
- 🧠 Uses **EfficientNet-B0** for powerful yet lightweight performance
- 🖼️ Supports **38 plant disease classes**
- 📱 Interactive **Streamlit UI** for real-time predictions
- 🌐 Deployed on Hugging Face Spaces for global access

---

## 📂 Dataset Overview

- 📦 Source: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- 📸 54,000+ labeled images
- 🌾 38 classes: Healthy + Diseased (Tomato, Apple, Corn, Grape, etc.)
- 💡 Preprocessing: Resizing, Normalization, Augmentation (RandomCrop, HorizontalFlip)

---

## 🧰 Tech Stack

- 🔥 **Framework**: PyTorch
- 🔍 **Model**: EfficientNet-B0 (Pretrained on ImageNet)
- 🎛️ **Frontend**: Streamlit
- ☁️ **Deployment**: Hugging Face Spaces
- 📊 **Evaluation Metrics**: Accuracy, Confusion Matrix

---

## 🏁 Getting Started

### 🔧 Installation

```bash
git clone https://github.com/darshnkd/PlantVisionAI.git
cd PlantVisionAI
