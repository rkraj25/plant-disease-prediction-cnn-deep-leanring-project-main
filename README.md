# 🌱 Plant Disease Classifier

A Deep Learning based **Plant Disease Classification** project that uses a Convolutional Neural Network (CNN) to identify plant diseases from leaf images.

The project includes a trained CNN model and a **Streamlit web application** where users can upload a plant leaf image and get the predicted disease.

---

## 🚀 Demo

The application allows the user to:

1. Upload a plant leaf image
2. Preview the uploaded image
3. Run the trained CNN model
4. Get the predicted plant disease

### 🖥️ Streamlit Application

![Plant Disease Classifier](images/app_screenshot.png)

Example prediction:

**Prediction: Potato___Early_blight**

---

## 📌 Features

- 🌿 Plant disease image classification
- 🧠 CNN-based deep learning model
- 🖼️ Upload and classify leaf images
- ⚡ Real-time prediction using Streamlit
- 🔥 TensorFlow/Keras model
- 📊 Image preprocessing and classification
- 💻 Simple and user-friendly web interface

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- Convolutional Neural Network (CNN)
- NumPy
- OpenCV
- PIL
- Streamlit
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

```text
plant-disease-prediction-cnn-deep-learning-project/
│
├── app/
│   ├── trained_model/
│   │   └── plant_disease_prediction_model.h5
│   │
│   ├── class_indices.json
│   ├── config.toml
│   ├── credentials.toml
│   ├── Dockerfile
│   ├── main.py
│   └── requirements.txt
│
├── model_training_notebook/
│   ├── class_indices.json
│   ├── Plant_Disease_Prediction_CNN_Image_Classifier.ipynb
│   └── plant_disease_prediction_model.h5
│
├── test_images/
│   ├── test_apple_black_rot.JPG
│   ├── test_blueberry_healthy.jpg
│   └── test_potato_early_blight.jpg
│
├── .gitignore
├── README.md
└── requirements.txt
