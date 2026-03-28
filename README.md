# 🎤 AI-Based Deepfake Voice Detection System

## 📌 Overview
This project focuses on detecting whether an audio sample is **real or AI-generated (deepfake)** using deep learning techniques.

With the rapid advancement of synthetic voice technologies, identifying manipulated audio is critical for ensuring security, authenticity, and preventing fraud. This system processes audio signals, converts them into spectrograms, and classifies them using a trained neural network model.

---

## 🚀 Features
- 🎧 Audio preprocessing and feature extraction  
- 📊 Spectrogram generation for model input  
- 🧠 Deep learning-based classification  
- 🔍 Detects Real vs Fake voice samples  
- 🗂️ Supports custom test audio inputs  

---

## 🧠 Tech Stack
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - PyTorch  
  - Librosa  
  - NumPy  
  - Matplotlib  

---

## 📁 Project Structure
DeepFake-Voice-Detection/
│── saved_models/ # Trained model files
│── src/
│ ├── app.py # Main application
│ ├── train.py # Model training
│ ├── dataset.py # Dataset handling
│ ├── model.py # Model architecture
│ ├── preprocess_audio.py # Audio preprocessing
│ ├── create_spectrogram.py
│ ├── inference.py # Prediction logic
│ ├── predict_utils.py
│── sample_audio/ # Test audio samples
│── requirements.txt
│── Dockerfile
│── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

git clone https://github.com/anshulverma1321/DeepFake-Voice-Detection.git

cd DeepFake-Voice-Detection


### 2️⃣ Install dependencies

pip install -r requirements.txt


---

## ▶️ Usage

### 🔹 Run prediction on audio file

python src/inference.py


### 🔹 Train the model (optional)

python src/train.py


---

## 📊 How It Works

1. Audio input is taken as a `.wav` file  
2. Audio is converted into a **spectrogram representation**  
3. Spectrogram is passed into a **deep learning model**  
4. Model predicts whether audio is:
   - Real ✅  
   - Fake ❌  

---

## 🔮 Future Improvements
- 🎤 Real-time microphone input detection  
- 🌐 Web interface using Streamlit or Flask  
- 📈 Confidence score visualization  
- ⚡ Model optimization for faster inference  

---

## 🎯 Applications
- Deepfake detection systems  
- Voice authentication security  
- Media verification  
- Fraud prevention  

---

## 👨‍💻 Author
**Anshul Verma**  
B.Tech CSE (AI & ML)

---

## ⭐ Acknowledgment
This project was developed and enhanced as part 
of hands-on learning in deep learning and audio processing.

---

## 📬 Contact
Feel free to connect for collaboration, suggestions, or discussions related to AI/ML project
