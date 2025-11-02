# ✋ Hand Gesture Recognition using MediaPipe & TensorFlow

> 🤖 A real-time AI system that detects and recognizes hand gestures using **MediaPipe**, **OpenCV**, and **TensorFlow** — turning simple hand movements into machine understanding!

---

## 📸 Project Overview

This project captures webcam images of hand gestures, extracts **21 landmark points** using Google’s **MediaPipe**, and trains a **Random Forest** model to classify gestures.  
You can then test the model live — your webcam recognizes your hand gestures and labels them in real time!

---

## ⚙️ Tech Stack

- 🧠 **TensorFlow / Keras** – preprocessing & data handling  
- 📷 **OpenCV** – image capture & live webcam testing  
- ✋ **MediaPipe** – hand landmark detection  
- 🌲 **Scikit-learn** – Random Forest classification  
- 🐍 **Python** – glue that brings it all together

---

## 🚀 Features

- Real-time webcam gesture detection  
- Automated dataset collection  
- MediaPipe hand landmark extraction  
- Model training & live prediction  
- Modular design — easy to customize gestures or algorithms  

---

## 🧩 Project Structure

sign-language/
│
├── datacollection.py # Capture hand gesture images
├── datapreprocessing.py # Extract hand landmarks & save as data.pickle
├── training.py # Train Random Forest model
├── test.py # Test model live with webcam
├── model.p # Trained model file
├── data.pickle # Processed dataset
└── Dataset/ # Captured images by class