# 💵 Egyptian Currency Detection AI

This project uses a trained TensorFlow Lite (TFLite) model to detect and classify Egyptian currency from images. It's designed to help visually impaired users or support smart assistant systems.

---

## 📦 Project Structure
currency_detector/
├── Untitled9 (1).py # Python script for detection
├── model.tflite # Trained TFLite model
├── labels.txt # Class labels (e.g., 5 EGP, 10 EGP)
├── detect.ipynb # Google Colab notebook
├── dataset/ # Example dataset (small preview)
│ ├── egp_5.jpg
│ ├── egp_10.jpg
│ └── labels.csv



---

## 🧠 Model Information

- **Model Type:** TensorFlow Lite (converted from Keras)
- **Input Shape:** (224, 224, 3)
- **Classes:** 5 EGP, 10 EGP, 20 EGP, 50 EGP, 100 EGP, 200 EGP
- **Use Case:** Blind assistance / mobile object recognition

---

## 🛠️ How to Use

Open detect.ipynb to test detection in the cloud.

##
📂 Full Dataset
Due to GitHub file size limits, the full training dataset is hosted externally:

🔗 Download Egyptian Currency Dataset from Google Drive

Total images: ~600

Classes: 5 EGP, 10 EGP, 20 EGP, 50 EGP, 100 EGP, 200 EGP

Format: .jpg images + labels.csv


## 
👤 Author
Mostafa Hani
GitHub: @Mostafa-Hani19

## ▶️ Run in Python (locally):

```bash
pip install tensorflow opencv-python numpy
python detect.py


