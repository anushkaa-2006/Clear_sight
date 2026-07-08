# 🚢 AI Cargo Risk Intelligence System

An AI-powered cargo inspection system that analyzes X-ray images and shipping manifests to detect suspicious cargo, identify undeclared objects, and assist customs and border security officers in making faster and more accurate inspection decisions.

## 📌 Features

- 📷 Upload cargo X-ray images
- 📄 Upload shipment manifest
- 🔍 Automatic object detection using YOLOv8
- 🧠 AI-based anomaly detection
- 📋 Manifest vs Detected Item comparison
- ⚠️ Cargo risk assessment (Safe / Suspicious)
- 📊 AI confidence scores
- 📈 Model contribution visualization
- 📝 Explainable AI (AI-generated inspection report)

---

## 🖥️ Demo

### Home Screen

- Enter Case ID
- Origin & Destination
- Container Number
- Upload Cargo X-ray
- Upload Manifest
- Run AI Analysis

### Analysis Results

- Declared Items
- Detected Objects
- Object Detection Visualization
- AI Explanation
- Risk Assessment
- AI Scores
- Model Contributions

---

## 🏗️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### AI & Machine Learning
- YOLOv8
- ResNet50
- CLIP
- OpenCV
- PyTorch
- NumPy
- Pillow

### Data Processing
- Pandas

---

## 📂 Project Structure

```
Clear_sight/
│
├── frontend/
│   └── app.py
│
├── inference/
│   ├── detect_objects.py
│   ├── risk_mapping.py
│   └── ...
│
├── pipeline/
│   └── full_pipeline.py
│
├── preprocessing/
│   └── ...
│
├── models/
│   ├── best.pt
│   └── anomaly_detection/
│
├── utils/
│
├── sample_data/
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/anushkaa-2006/Clear_sight.git
cd Clear_sight
```

### Create Virtual Environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run frontend/app.py
```

The application will start at

```
http://localhost:8501
```

---

## 🧠 AI Pipeline

1. Upload X-ray Image
2. Preprocess Image
3. Detect Objects using YOLOv8
4. Extract Visual Features
5. Compare with Manifest
6. Perform Anomaly Detection
7. Compute Risk Score
8. Generate Explainable AI Report
9. Display Results

---

## 📊 Output

The system provides:

- Detected Cargo Items
- Bounding Boxes
- Detection Confidence
- Declared vs Detected Comparison
- AI Explanation
- Suspicious Cargo Detection
- Risk Score
- AI Model Contributions

---

## 📸 Sample Output

- Cargo X-ray with detected objects
- AI-generated inspection report
- Suspicious cargo identification
- Risk assessment dashboard

---

## Future Enhancements

- OCR for automatic manifest extraction
- Grad-CAM visual explanations
- Real-time CCTV cargo inspection
- Multi-class hazardous material detection
- Container tracking integration
- Cloud deployment
- Customs officer dashboard

---

## 👩‍💻 Team

Developed for **Tesseract Hackathon**.

---

## 📄 License

This project is developed for educational and research purposes.
