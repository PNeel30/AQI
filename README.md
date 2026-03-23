# 🌫️ Air Quality Index Dashboard (AirWatch India)

AI-powered interactive dashboard to monitor and visualize air pollution levels across Indian cities. This project provides insights into AQI metrics, pollution trends, and health impacts using an intuitive Streamlit interface.

---

## ✨ Key Features

### 📊 Real-Time AQI Visualization
- Displays air pollution data across India
- Interactive UI with charts and visuals
- Image-based AQI overview

### 🌍 Pollution Metrics Tracking
- PM2.5, PM10, NO2, CO, and other pollutants
- Easy-to-understand representation
- City-level awareness

### 🧠 Health Insights
- Explains impact of air pollution on:
  - Respiratory health
  - Cardiovascular diseases
  - Life expectancy
- Educational and awareness-focused content

### 🎨 User-Friendly Interface
- Built with Streamlit
- Clean and responsive UI
- Visual storytelling with images and text

---

## 🏗️ Architecture

```
User → Streamlit UI → Python Logic → AQI Visualization → Output Dashboard
```

---

## 📂 Project Structure

```
AQI/
│
├── 📊 Air_Quality_Index.py     # Main Streamlit application
├── 📓 Model.ipynb              # Data analysis / experimentation
├── 🖼️ India-2023.png           # AQI visualization image
├── 🖼️ air.jpeg                # UI asset
├── 🎥 output_video.webm       # Demo video (optional)
│
├── 📦 Configuration
│   ├── requirements.txt       # Dependencies
│   └── .gitignore            # Ignore rules
│
└── 📖 README.md              # Documentation
```

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Streamlit installed
- Basic knowledge of Python

---

## 📁 Setup Instructions

### 1️⃣ Clone Repository
```bash
git clone <your-repo-link>
cd AQI
```

### 2️⃣ Create Virtual Environment
```bash
python -m venv .venv

# Activate (Windows)
.\.venv\Scripts\activate

# Activate (Mac/Linux)
source .venv/bin/activate
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run Air_Quality_Index.py
```

👉 App will open at:
http://localhost:8501

---

## 🛠️ Technology Stack

### Frontend
- Streamlit

### Backend
- Python
- Pandas (optional)

---

## 🎯 Key Design Decisions

- Simple UI-first approach
- Educational focus
- Lightweight architecture
- Streamlit-based design

---

## 🚀 Future Improvements

- Real-time AQI API integration
- City-wise filtering
- Advanced analytics
- Cloud deployment
- AI-based AQI prediction

---

