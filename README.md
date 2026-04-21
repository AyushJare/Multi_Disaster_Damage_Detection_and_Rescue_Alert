# 🌍 Disaster Assessment & Response System

An AI-powered full-stack application that analyzes satellite imagery to detect disasters, assess damage severity, and recommend emergency response actions in real time.

This system compares pre- and post-disaster images using deep learning models and provides actionable insights for faster and smarter rescue operations.

---

## 🚀 Tech Stack

**Frontend:** React.js, Tailwind CSS
**Backend:** Flask (Python), Flask-CORS
**Machine Learning:** PyTorch, Torchvision
**Tools:** Google Colab, VS Code, Git

---

## 🧠 Models Used

* **MobileNetV2** — Lightweight & fast inference
* **EfficientNet Lite** — Balanced accuracy & efficiency
* **ShuffleNet** — Optimized for performance on low-resource systems

All models are trained on satellite imagery datasets to classify:

* Disaster type (Flood, Earthquake, Fire, etc.)
* Damage severity

---

## ✨ Features

* 📸 Upload **Before & After Satellite Images**
* 🤖 Select AI model or run **multi-model comparison**
* 🧠 Detect disaster type automatically
* 📊 Estimate **damage percentage**
* 🚨 Classify urgency level (Low / High / Critical)
* 👨‍🚒 Recommend number of rescue teams required
* 📈 Visual dashboard with model-wise predictions
* ⚡ Fast and interactive UI for real-time analysis

---

## 🖥️ UI Highlights

* Modern glassmorphism-based design
* Image preview before processing
* Dynamic damage progress bar
* Urgency indicator badges
* Model comparison cards
* Smooth animations and responsive layout

---

## 📂 Project Structure

```
project-assessment/
│
├── backend/
│   ├── app.py                # Flask API
│   ├── models/               # Trained .pth model files
│   │   ├── mobilenet.pth
│   │   ├── efficientnet.pth
│   │   └── shufflenet.pth
│   └── venv/                 # Virtual environment
│
├── frontend/
│   ├── src/
│   │   ├── App.js            # Main React UI
│   │   ├── index.js
│   │   └── index.css         # Tailwind styles
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Getting Started

### 🔧 Prerequisites

* Node.js installed
* Python 3.10+
* Git installed

---

## 🛠️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/AyushJare/disaster-assessment
cd disaster-assessment
```

---

### 2. Setup Backend

```bash
cd backend

# Create virtual environment
python -m venv venv

# Activate it
venv\Scripts\activate   # Windows

# Install dependencies
pip install flask flask-cors torch torchvision pillow

# Run backend
python app.py
```

---

### 3. Setup Frontend

```bash
cd frontend

# Install dependencies
npm install

# Start React app
npm start
```

---

## 🌐 Application Flow

```
User Uploads Images
        ↓
Frontend (React UI)
        ↓
API Request
        ↓
Backend (Flask + Models)
        ↓
AI Prediction
        ↓
Results Displayed (Damage + Urgency)
```

---

## 📊 Output Example

* Disaster Type: Flood
* Damage Level: 75%
* Urgency: 🔴 Critical
* Recommended Teams: 8
* Model Comparison Results

---

## 🔮 Future Scope

* 🛰️ Integration with real-time satellite imagery APIs
* 📍 Live disaster mapping using geolocation (Mapbox / Leaflet)
* 🌡️ Heatmap visualization of affected regions
* 🤖 Edge AI deployment using Raspberry Pi / Jetson Nano
* 📡 Automatic alert system for disaster management authorities
* 🧠 Improved accuracy using larger datasets (xBD, Sentinel, Maxar)
* ☁️ Cloud deployment for global accessibility

---

## 👨‍💻 Author

**Ayush Jare**
GitHub: https://github.com/AyushJare
LinkedIn: https://linkedin.com/in/ayushjare

---

## ⭐ Note

This project is being developed as a major academic project demonstrating the use of AI in disaster management and real-world problem solving.
