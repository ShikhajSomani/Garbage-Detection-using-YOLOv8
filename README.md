# ♻️ Garbage Detection using YOLOv8

An AI-powered garbage detection system built using **YOLOv8**, **FastAPI**, and **PyTorch**.
The system detects multiple garbage objects in an uploaded image and returns predictions with confidence scores through a REST API.

---

# 🚀 Live Deployment

### Backend API (Render)

https://garbage-detection-api-dqwj.onrender.com/

### Interactive Swagger API Docs

https://garbage-detection-api-dqwj.onrender.com/docs

---

# 📌 Features

✅ Multi-object garbage detection
✅ YOLOv8 custom-trained model
✅ Confidence score prediction
✅ FastAPI REST API backend
✅ Render cloud deployment
✅ Real-time inference support
✅ Lightweight YOLOv8n model
✅ Deployment-ready architecture

---

# 🛠️ Tech Stack

| Technology | Purpose                 |
| ---------- | ----------------------- |
| Python     | Programming Language    |
| YOLOv8     | Object Detection Model  |
| PyTorch    | Deep Learning Framework |
| FastAPI    | Backend API             |
| Uvicorn    | ASGI Server             |
| OpenCV     | Image Processing        |
| Render     | Cloud Deployment        |

---

# 🧠 Model Details

* Model Used: **YOLOv8n**
* Framework: **PyTorch**
* Task: **Object Detection**
* Deployment Format: `.pt`
* Detection Type: **Multi-Class Garbage Detection**

---

# 📂 Project Structure

```bash
Garbage-Detection-using-YOLOv8/
│
├── main.py
├── best.pt
├── requirements.txt
├── uploads/
├── .gitignore
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/ShikhajSomani/Garbage-Detection-using-YOLOv8.git

cd Garbage-Detection-using-YOLOv8
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run FastAPI Server

```bash
uvicorn main:app --reload
```

Server runs on:

```bash
http://127.0.0.1:8000
```

---

# 📡 API Documentation

FastAPI automatically generates Swagger documentation:

```bash
http://127.0.0.1:8000/docs
```

---

# 📤 API Endpoint

## POST `/predict`

Upload an image and receive garbage detection predictions.

---

# 📥 Sample Response

```json
{
  "detections": [
    {
      "class": "plastic bottle",
      "confidence": 94.21
    },
    {
      "class": "can",
      "confidence": 88.47
    }
  ]
}
```

---

# ☁️ Deployment

The backend API is deployed using:

* FastAPI
* Uvicorn
* Render

Deployment command:

```bash
uvicorn main:app --host 0.0.0.0 --port $PORT
```

---

# 🔍 Future Improvements

* Streamlit/React Frontend
* Webcam Detection
* Real-Time Video Detection
* Recycling Suggestions
* Mobile Application Integration
* Docker Support

---

# 📚 Learning Outcomes

This project helped in understanding:

* Object Detection using YOLOv8
* Transfer Learning
* FastAPI Backend Development
* Model Deployment
* REST APIs
* Cloud Deployment using Render

---

# 👨‍💻 Author

## Shikhaj Somani

---

