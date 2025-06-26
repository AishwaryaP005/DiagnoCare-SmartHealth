# 🏥DiagnoCare – AI-Powered Healthcare Assistance Platform

**DiagnoCare** is a unified, AI-driven healthcare platform designed to assist users with disease prediction, personalized care, health monitoring, and emergency support through a user-friendly web interface.

---

## 📌Objective

To develop an intuitive and intelligent healthcare system that provides:
- AI-based disease diagnosis (e.g., pneumonia from X-rays, symptom-based prediction)
- Personalized diet and medication planning
- Health record management and visualization
- Emergency SOS integration with real-time hospital mapping
- Direct Doctor-patient communication and secure file exchange

---

## 📌Problem Statement

Despite technological advancements, healthcare still faces challenges such as:
- Delayed diagnosis due to limited access to specialists  
- Lack of personalized treatment plans  
- Poor emergency response systems  
- Communication gaps between doctors and patients

---

## 📌Solution: DiagnoCare

A modular healthcare assistant that offers:
- AI-powered disease prediction using deep learning and rule-based logic
- Diet recommendations based on BMI and medical conditions
- Centralized digital health record management with downloadable reports
- Emergency SOS integration with real-time nearby hospital mapping
- Voice and chatbot-based health assistance

---

## 📌Key Features

- Pneumonia Detection via Chest X-rays (PyTorch + TorchXRayVision)
- Symptom-based Disease Prediction
- Personalized Diet Planning
- AI Chatbot (Google Gemini API) and Voice Tips (pyttsx3)
- Digital Health Reports (FPDF)
- Emergency SOS with Map-Based Hospital Locator (Folium)
- Appointment Booking and Health Record Storage (MySQL)
- Data Visualizations (Plotly, Seaborn, Matplotlib)

---

## 📌Tech Stack

### Frontend
- Streamlit – Web UI
- Plotly / Seaborn / Matplotlib – Data visualization
- Folium – Interactive maps
- Pillow – Image upload and preview
- HTML/CSS – Custom styling within Streamlit

### 📌Backend
- Python – Core logic and processing
- PyTorch + TorchXRayVision – Deep learning for medical imaging
- scikit-learn – Symptom analysis and diet prediction
- pandas / numpy – Data handling and preprocessing
- Google Gemini API – AI-powered health chatbot
- pyttsx3 / gTTS – Voice-based health tips

### 📌Database & File Management
- MySQL – Data storage for users, appointments, and records
- os, fpdf, reportlab – File handling and PDF report generation
- Joblib – Saving and loading ML models

---

## 📌Features Covered

- Secure login for patients and doctors
- Upload and manage medical records
- Interactive charts for health trends and disease analysis
- Appointment booking and management
- PDF generation for health reports
- Real-time SOS alerts and hospital locator
- Voice-based playback of health tips for accessibility
- Personalized diet plans based on health data
- Disease prediction from symptom selection

---

## 📌Video

**https://drive.google.com/file/d/1-CmApXOKZDljdTf45f4BWLQ9qejB3V33/view?usp=sharing**

---

## 📌Impact

- Faster and more accurate diagnosis through AI-based automation
- Tailored healthcare recommendations based on individual data
- Improved emergency response with integrated location services
- Centralized and accessible digital health record management

---


## 📌Getting Started

1. Clone the repository 
2. Install dependencies
  pip install -r requirements.txt
3. Configure the database
  Update your MySQL credentials in database/config.py
4. Run the application
  streamlit run app.py

---
