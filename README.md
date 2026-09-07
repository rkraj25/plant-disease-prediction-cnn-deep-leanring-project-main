# 🌱 Plant Disease Classifier

A **Deep Learning project** that uses a **Convolutional Neural Network (CNN)** to classify plant diseases from leaf images.

The trained model is integrated with a **Streamlit web application** for disease prediction.

## 🚀 Features

- 🌱 Plant disease classification
- 🧠 CNN-based deep learning model
- 🖼️ Upload leaf images
- ⚡ Real-time prediction
- 🌐 Streamlit web application
- 📊 Model evaluation
- 🧪 Sample test images
- 🐳 Docker support

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- CNN
- NumPy
- OpenCV
- Pillow
- Streamlit
- Jupyter Notebook
- Docker

## 🌾 Dataset

This project uses the **PlantVillage Dataset**.

[Kaggle PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)

The complete dataset is not included because of its large size.

## 📂 Project Structure

```text
app/
├── trained_model/
├── class_indices.json
├── main.py
├── requirements.txt
└── Dockerfile

images/
└── Screenshot (3041).png

model_training_notebook/
└── Plant_Disease_Prediction_CNN_Image_Classifier.ipynb

test_images/
├── test_apple_black_rot.JPG
├── test_blueberry_healthy.jpg
└── test_potato_early_blight.jpg

README.md
└── .gitignore
```

## 🧠 CNN Workflow

**Leaf Image → Preprocessing → CNN → Classification → Predicted Disease**

The CNN learns features such as edges, shapes, colors, textures, and disease patterns.

## 📊 Model Performance

| Metric | Score |
|---|---:|
| Accuracy | **90.02%** |
| Precision | **88.01%** |
| Recall | **85.47%** |
| F1-Score | **86.36%** |

## 🌐 Streamlit Application

Users can:

1. Upload a plant leaf image
2. Preview the image
3. Process the image
4. Get the predicted disease

![Plant Disease Classifier](images/Screenshot%20%283041%29.png)

### Example Prediction

**Input:** `test_potato_early_blight.jpg`

**Prediction:** `Potato___Early_blight`

## 📓 Model Training

The training notebook is available in:

`model_training_notebook/Plant_Disease_Prediction_CNN_Image_Classifier.ipynb`

It includes data loading, preprocessing, CNN creation, training, validation, evaluation, and model saving.

## ⚙️ Installation

```bash
git clone https://github.com/rkraj25/plant-disease-prediction-cnn-deep-leaning-project-main.git
cd plant-disease-prediction-cnn-deep-leaning-project-main
python -m venv venv
venv\Scripts\activate
pip install -r app/requirements.txt
```

## ▶️ Run the Application

```bash
cd app
streamlit run main.py
```

The application will normally open at `http://localhost:8501`.

## 🐳 Docker

```bash
docker build -t plant-disease-classifier ./app
docker run -p 8501:8501 plant-disease-classifier
```

## ⚠️ Limitations

Prediction performance may be affected by image quality, lighting, background, unseen diseases, and images that differ from the training data.

This project is intended for **educational and research purposes**.

## 🔮 Future Improvements

- Improve accuracy
- Use Transfer Learning
- Add more diseases and plant species
- Add prediction confidence
- Add confusion matrix
- Deploy online
- Add treatment recommendations

## 🏷️ Topics

`python` `deep-learning` `cnn` `tensorflow` `keras` `computer-vision` `plant-disease` `machine-learning` `image-classification` `streamlit`

## 👨‍💻 Author

**Raj Karmankar**

[GitHub](https://github.com/rkraj25)

## ⭐ Support

If you like this project, consider giving the repository a ⭐.

## 📜 License

For **educational and research purposes**.
