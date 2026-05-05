# 🥔 Potato Leaf Disease Detection

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

A Deep Learning-based web application that detects diseases in potato plants from leaf images. The model is trained using a Convolutional Neural Network (CNN) built with TensorFlow/Keras, and the user-friendly frontend is powered by Streamlit.

## ✨ Features
* **Image Upload**: Users can easily upload images of potato leaves (JPG, JPEG, PNG).
* **Real-time Prediction**: Instantly classifies the leaf into one of three categories:
  * 🍂 Early Blight
  * 🍂 Late Blight
  * 🌿 Healthy
* **Confidence Score**: Displays the model's prediction confidence level with an intuitive progress bar and status indicator.
* **Custom UI**: Features custom-styled banners and a clean, responsive layout.

## 🛠️ Tech Stack
* **Machine Learning**: TensorFlow, Keras
* **Frontend**: Streamlit, HTML/CSS
* **Data Processing**: NumPy, Pillow (PIL)
* **Dataset**: [Potato Plant Diseases Data](https://www.kaggle.com/datasets/hafiznouman786/potato-plant-diseases-data) (via Kaggle)

## 📂 Project Structure
```text
├── app.py                         # Main Streamlit application script
├── potato_disease_model.h5        # Saved trained CNN model
├── Potato_Leaf_Disease_Detection.ipynb # Google Colab notebook for training the model
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation
