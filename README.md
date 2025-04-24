# 🧠 Deepfake Detection in Social Media Content

A web-based deepfake detection tool built using **Streamlit**, **TensorFlow**, and **OpenCV**. This project helps users determine whether an image is real or synthetically generated using deep learning techniques.

## 🚀 Overview

With the rise of AI-generated synthetic media, it's becoming increasingly difficult to distinguish between real and fake content. This application enables users to upload an image and determine whether it's **real** or **fake** using a pre-trained Convolutional Neural Network (CNN) model.

The model has been trained to detect visual anomalies typically found in deepfake images, such as:

- Inconsistencies in lighting and shadows
- Mismatched facial features
- Irregular textures and artifacts

---

## 🖥️ Live Demo

> _A live version can be deployed on platforms like **Streamlit Community Cloud**, **Heroku**, or **Render**._

---

## 📷 Features

- Upload `.jpg`, `.jpeg`, or `.png` image files
- Image preview after upload
- Instant prediction result with color-coded classification
- Model performance summary
- Informational content about deepfakes and their risks

---

## 🧰 Tech Stack

- **Frontend:** Streamlit
- **Backend:** TensorFlow (Keras), NumPy, OpenCV
- **Model:** CNN trained for binary classification (Real vs Fake)

---

## 🏗️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/deepfake-detection-app.git
cd deepfake-detection-app
