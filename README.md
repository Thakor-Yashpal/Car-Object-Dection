 # Car Object Detection with YOLOv8 and OpenCV

This project implements a car object detection pipeline using YOLOv8 and OpenCV. It allows you to detect and localize cars in images or videos.

## 🔍 Overview

This project leverages the power of YOLOv8 for real-time object detection and OpenCV for image and video processing. It's designed to be easily deployed and used for various applications.

## 🚀 Features

- **Car Detection:** Detects cars in images and videos.
- **YOLOv8:** Uses the state-of-the-art YOLOv8 object detection model from Ultralytics.
- **OpenCV:** Employs OpenCV for image and video handling.
- **Easy Setup:** Simple installation using `pip` and the provided `requirements.txt`.
- **API Endpoint (Optional):** Provides a Flask-based API endpoint for easy integration with other applications.

## 📁 Requirements

- Python 3.7+
- pip

## ⚙️ Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Thakor-Yashpal/Car-Object-Detection.git
    cd Car-Object-Detection
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

---

## 📊 Notebooks & Demos

### 📘 Kaggle Notebook
[🔗 View on Kaggle](https://www.kaggle.com/<your-kaggle-username>/<your-notebook-slug>)

### 📓 Google Colab
[🚀 Run in Colab](https://colab.research.google.com/drive/1Rz_KCzqYRyhczrLulhXU0TK02Lo2pxpR#scrollTo=UAYyCUJdbD47>)

> 💡 You can directly test the pipeline in Colab without setting up anything locally.

---

## 🔌 API Usage (Optional)

If you're using the Flask API (`app.py`):

1. Run the server:

    ```bash
    python app.py
    ```

2. Send a POST request:

    ```bash
    curl -X POST -F frame=@frame.jpg http://localhost:5000/detect
    ```

---
