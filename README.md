# Fracture-Scan
# 🩻 Fracture Detection in X-Ray Images using TensorFlow 2.0

FractureDetect is an AI-powered web app that detects bone fractures from X-ray images using a Convolutional Neural Network (CNN) built with TensorFlow 2.0. It enables users to upload X-rays and receive real-time fracture classification and bounding box visualization.

## 📌 Features

- Classifies X-ray images as fractured or not
- Optional: Detects and highlights fracture regions using bounding boxes
- Built with TensorFlow 2.0 and Streamlit
- Designed for educational and assistive healthcare purposes

---

## 🧠 Technologies Used

- TensorFlow 2.0 + Keras
- CNN architecture
- TensorFlow Object Detection API (for bounding box detection)
- OpenCV & PIL for image processing
- Streamlit for web interface
- Google Colab for training
- Annotation using LabelImg / Roboflow

---

## 🗃️ Dataset

- MURA Dataset by Stanford (X-rays of limbs with fracture/abnormal labels)
- Or fracture-labeled datasets from Roboflow (YOLO-ready)
- Format: `.jpg/.png` X-ray images with `.xml` or `.txt` annotation files

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/fracture-detection-xray-tf.git
cd fracture-detection-xray-tf
pip install -r requirements.txt
