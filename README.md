# 🌿 PlantCare AI – Intelligent Plant Disease Detection

An AI-powered plant health analysis application that uses deep learning to identify possible plant diseases from leaf images.

PlantCare AI allows users to upload a plant leaf image or capture one using their camera and receive an AI-generated disease prediction with confidence scores.

## 🚀 Live Demo

**Try the application here:**

https://plantdiseaseprediction-suar.streamlit.app/

Explore plant disease detection directly through your browser without installing anything!

---

## ✨ Features

- **AI-Based Disease Detection:** Identifies possible plant disease classes using a trained deep learning model.
- **Image Upload:** Upload leaf images in JPG, JPEG, and PNG formats.
- **Live Camera Capture:** Capture plant images directly through your device camera.
- **Prediction Confidence:** Displays the model's confidence score.
- **Top Predictions:** Shows the top three predicted disease classes.
- **Interactive Dashboard:** Modern, clean, and user-friendly interface.
- **Fast Predictions:** Uses TensorFlow for image classification.

---

## 🧠 How It Works

PlantCare AI uses a trained **MobileNetV2** deep learning model to classify plant leaf images.

### Prediction Workflow

1. Upload or capture a plant leaf image.
2. Convert the image into RGB format.
3. Resize the image to 224 × 224 pixels.
4. Process the image using the trained TensorFlow model.
5. Generate prediction scores for different disease classes.
6. Display the predicted disease, confidence score, and top three predictions.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow | Deep learning |
| MobileNetV2 | Image classification |
| Streamlit | Web application |
| NumPy | Numerical operations |
| Pillow (PIL) | Image processing |
| PlantVillage | Dataset |

---

## 📂 Project Structure

```text
PlantCare-AI/
│
├── app.py
│
├── plant_disease_model.keras
│
├── class_names.npy
│
├── requirements.txt
│
└── README.md
```

### Important Files

- `app.py` – Main Streamlit application.
- `plant_disease_model.keras` – Trained deep learning model.
- `class_names.npy` – Contains disease class labels.
- `requirements.txt` – Python dependencies.
- `README.md` – Project documentation.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/PlantCare-AI.git
```

### 2. Navigate to the Project Directory

```bash
cd PlantCare-AI
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
streamlit run app.py
```

Open the application at:

```text
http://localhost:8501
```

---

## 📦 Requirements

Create a `requirements.txt` file with:

```text
streamlit
tensorflow
numpy
Pillow
```

---

## 📊 Dataset

This project uses the **PlantVillage Dataset**, a publicly available collection of plant leaf images containing healthy and diseased plant samples.

The dataset is used to train an image classification model capable of recognizing different plant disease categories.

---

## ⚠️ Disclaimer

PlantCare AI provides AI-generated predictions for informational purposes only.

Predictions are not guaranteed to be accurate and should not replace professional agricultural diagnosis. Consult an agricultural expert before making plant-treatment decisions.

---

## 🚀 Future Enhancements

- Improve model accuracy through fine-tuning.
- Add more plant species and disease categories.
- Provide disease descriptions and symptoms.
- Include prevention and treatment recommendations.
- Add prediction history.
- Improve performance on real-world plant images.

---

## 👩‍💻 Developer

**Pooja Bisht**

Developed with ❤️ using Python, TensorFlow, and Streamlit.

---

<p align="center">
  🌿 <b>PlantCare AI</b><br>
  Making plant health analysis smarter.
</p>
