# 🔍 TruthLens

**TruthLens** is an AI-powered fake news detection web app built with **Python, Flask, Machine Learning, and OCR**.

It allows users to check news by entering **text** or uploading a **news screenshot/image**.

## ✨ Features

- 📰 Fake/Real news detection
- 🖼️ News screenshot analysis
- 🔎 OCR text extraction from images
- 📊 Prediction confidence score
- 🔐 User authentication
- 📚 Analysis history
- 📄 Downloadable reports
- 🌐 English & Hindi support

## 🧠 How It Works

```text
Text / Image
     ↓
OCR (for images)
     ↓
TF-IDF
     ↓
Machine Learning Model
     ↓
Real / Fake Prediction
     ↓
Confidence + Explanation
```

## 🛠️ Tech Stack

- **Python**
- **Flask**
- **Scikit-learn**
- **TF-IDF**
- **PassiveAggressiveClassifier**
- **Tesseract OCR**
- **Pillow**
- **SQLite**
- **HTML / CSS / JavaScript**
- **Docker**

## 🚀 Run Locally

```bash
git clone https://github.com/SourabhDhulrao/TruthLens.git
cd TruthLens

pip install -r requirements.txt

python app.py
```

Open:

```text
http://localhost:5000
```

## 🌐 Live Demo

**[TruthLens Live](https://truthlens-st4p.onrender.com/)**

## 👨‍💻 Author

**Sourabh Dhulrao**

[GitHub](https://github.com/SourabhDhulrao)

> ⚠️ TruthLens is an educational project. Predictions should not be considered definitive proof that a news claim is true or false.
