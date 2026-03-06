# 🐛 Crop Pest Detection and Classification Using Deep Learning Techniques

🚀 **Live Application:**  
https://deeppest-app-ktdtcnpreajqud8z8j7a6o.streamlit.app/

---

## 📌 Project Overview

Agricultural productivity is significantly affected by crop pests, which cause severe yield losses and economic damage worldwide. Manual pest detection is time-consuming, inaccurate, and impractical for large-scale farming environments.

This project presents an **AI-powered crop pest detection system** using **Deep Learning techniques** to automatically identify and classify pests from agricultural images.

The proposed model integrates:

- **EfficientNet-B4** for feature extraction
- **DeepestNet classifier** for multi-class pest classification

The system achieves **high accuracy (95.4%)** while maintaining **low computational complexity**, making it suitable for **real-time agricultural applications and edge devices**.

---

## 🎯 Objectives

- Detect crop pests automatically from images
- Improve pest classification accuracy using deep learning
- Reduce excessive pesticide usage
- Enable **precision agriculture and smart farming**
- Support **real-time pest monitoring**

---

## 🧠 Proposed Architecture

The system uses a **DeepestNet + EfficientNet-B4 architecture** for efficient pest detection.

### Workflow

1️⃣ Input Image  
2️⃣ Image Preprocessing  
3️⃣ Feature Extraction using EfficientNet-B4  
4️⃣ DeepestNet Classification  
5️⃣ Pest Category Prediction with Confidence Score

---

## ⚙️ Methodology

### Dataset Preparation

- Field-collected pest images
- Image resizing: **380 × 380**
- Data augmentation:
  - Rotation
  - Flipping
  - Contrast enhancement

### Training Configuration

| Parameter | Value |
|-----------|------|
| Feature Extractor | EfficientNet-B4 |
| Classifier | DeepestNet |
| Loss Function | Categorical Cross Entropy |
| Optimizer | Adam |
| Learning Rate | 0.0001 |
| Batch Size | 32 |
| Epochs | 50 |
| Dropout | 0.4 |
| Train/Test Split | 80% / 20% |

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|------|------|------|------|------|
| Faster R-CNN | 88.5% | 85.2% | 86.8% | 86.0% |
| YOLOv5 | 91.2% | 89.5% | 90.3% | 89.9% |
| Traditional CNN | 85.7% | 83.1% | 82.5% | 82.8% |
| **DeepestNet + EfficientNet-B4** | **95.4%** | **94.1%** | **94.8%** | **94.4%** |

---

## 🌱 Applications

- Precision Agriculture
- Smart Farming Systems
- Automated Pest Monitoring
- Agricultural Drone Monitoring
- Edge Device Pest Detection

---

## 🛠️ Technologies Used

- **Python**
- **TensorFlow / Keras**
- **EfficientNet-B4**
- **Deep Learning**
- **Streamlit**
- **Computer Vision**
- **Image Processing**

---

## 🖥️ Web Application

This project is deployed as a **Streamlit web application** where users can upload crop images and detect pests instantly.

🔗 Live Demo:  
https://deeppest-app-ktdtcnpreajqud8z8j7a6o.streamlit.app/

---

## 📂 Project Structure

```
Crop-Pest-Detection
│
├── dataset
├── models
├── training
├── app.py
├── requirements.txt
└── README.md
```

---

## 🔮 Future Improvements

- Deploy on **edge devices and drones**
- Integrate **IoT-based pest monitoring**
- Expand pest dataset for higher accuracy
- Implement **Explainable AI (XAI)** for better model interpretation
- Real-time field monitoring systems

---

## 👨‍🏫 Authors

### Dr. D. Ganesh  
Associate Professor, Dept. of CSE  
School of Computing  
Mohan Babu University, Tirupati, Andhra Pradesh, India  
📧 dgani05@gmail.com  

### Dr. M. Sunil Kumar  
Professor, Dept. of CSE  
Mohan Babu University  
📧 sunilmalchi1@gmail.com  

### Munthala Lakshmi Tejaswi  
UG Scholar, Dept. of CSE  
Mohan Babu University, Tirupati  
📧 mltejaswi1@gmail.com  

### Pidugu Vanaja  
UG Scholar, Mohan Babu University  
📧 vanajapidugu031@gmail.com  

### Rayachoti Bharath Kumar  
UG Scholar, Mohan Babu University  
📧 bharath170204@gmail.com  

### Sharabu Ajith Kumar  
UG Scholar, Mohan Babu University  
📧 sharabuajithkumar7@gmail.com  

---

## 📚 References

1. Mallick et al., *Deep learning based automated disease detection and pest classification in Indian mung bean*, Multimedia Tools and Applications, 2023.  
2. Sanghavi et al., *Deep CNN for Crop Pest Identification*, Evolving Systems, 2023.  
3. Reshmy et al., *Deep Learning Framework for Crop Pest Classification*, IEEE ICAIT, 2024.  

---

## ⭐ If you like this project

Please consider **starring ⭐ the repository** to support the work.
