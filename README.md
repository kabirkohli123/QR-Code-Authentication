# QR Code Authentication: Detecting Original vs. Counterfeit Prints

## 📌 Project Overview
This project aims to classify QR codes as **Original (First Print)** or **Counterfeit (Second Print)** using **Machine Learning and Deep Learning** techniques. The model helps in detecting counterfeit QR codes that are created by scanning and reprinting original QR codes.

## 🚀 Features
- **Data Preprocessing**: Resizes, normalizes, and augments QR code images.
- **Feature Engineering**: Extracts key image features using **Local Binary Patterns (LBP)** and **Edge Detection**.
- **Traditional ML Model**: Implements **Random Forest Classifier** for classification.
- **Deep Learning Model**: A **Convolutional Neural Network (CNN)** for higher accuracy.
- **Performance Evaluation**: Generates **confusion matrices, classification reports, and training metrics**.
- **Deployment Ready**: Designed for mobile apps, web APIs, and edge AI (Raspberry Pi, Jetson Nano).

## 🛠 Tech Stack
- **Python**
- **OpenCV** for image processing
- **Scikit-Learn** for machine learning
- **TensorFlow/Keras** for deep learning
- **Matplotlib & Seaborn** for visualization

## 📂 Dataset Structure
```
QRCode_Dataset/
│── First Print/    # Folder containing original QR codes
│── Second Print/   # Folder containing counterfeit QR codes
```

## 📊 Model Performance
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|----------|----------|--------|---------|
| Random Forest | 95.% | 95% | 95% | 95% |
| CNN | 95% | 91% | 100% | 95% |

## 🔧 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/kabirkohli123/QR-Code-Authentication.git
   cd QR-Code-Authentication
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## 🤝 Contributing
Pull requests are welcome! Feel free to open an issue for discussions.

---
🔗 **Project Maintainer:** [Your Name](https://github.com/your-username)

