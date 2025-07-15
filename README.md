# 😄 Real-Time Facial Emotion Detection (Google Colab)

This project enables real-time facial emotion recognition through your webcam in Google Colab. Using a CNN trained on the FER2013 dataset and OpenCV’s Haar Cascade, it detects facial expressions like Happy, Sad, Angry, and more — directly in your browser!

---

## 📦 Features

- Real-time webcam-based emotion detection in Colab
- CNN model trained on FER2013 dataset
- Haar Cascade face detection (OpenCV)
- Interactive JS + Python webcam UI
- Annotated face bounding boxes with emotion labels

---

## 💻 Technologies Used

- **TensorFlow/Keras** – for emotion classification
- **OpenCV** – for face detection
- **JavaScript** – interactive webcam UI in notebook
- **Google Colab** – runs entirely in your browser
- **FER2013 Dataset** – 7-class facial emotion data

---

## 🧠 Emotion Classes Detected

- Angry  
- Disgust  
- Fear  
- Happy  
- Sad  
- Surprise  
- Neutral

---

## 🚀 How to Use

1. **Open the Notebook**: [`emotion_detection.ipynb`](./emotion_detection.ipynb)
2. **Run Cells in Order**:
   - **Cell 1**: Imports & Setup
   - **Cell 2**: Load model and Haar Cascade
   - **Cell 3**: Python detection callback
   - **Cell 4**: JavaScript webcam UI
3. **Allow Webcam** access when prompted
4. Click **"Capture & Detect"** to classify your emotion!
5. Your face will be labeled with the predicted emotion and confidence

---
