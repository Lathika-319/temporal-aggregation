# ⏳ Temporal Aggregation for Video Behavior Analysis

A machine learning project developed during the UpToSkills Virtual Internship that performs temporal aggregation on surveillance videos to analyze human movement and classify activities using computer vision and machine learning.

---

## 📖 Project Overview

This project applies temporal aggregation techniques to CCTV videos for behavioral analysis. It detects people in video frames using YOLOv8, extracts temporal movement features such as speed and area changes, and classifies activities using a Random Forest classifier.

The implementation was developed and tested using Kaggle Notebook.

---

## 🎯 Objectives

- Detect people from surveillance videos.
- Extract temporal movement features.
- Analyze motion patterns across consecutive frames.
- Classify activities using machine learning.
- Demonstrate video-based behavior analysis.

---

## 📂 Dataset

The project uses publicly available video datasets for experimentation.

> The dataset is not included in this repository due to its size.

---

## 🧹 Data Preprocessing

- Video frame extraction
- Person detection using YOLOv8
- Motion feature extraction
- Speed calculation
- Area variation analysis
- Feature aggregation

---

## 🤖 Model Development

The workflow includes:

- YOLOv8 object detection
- Temporal feature extraction
- Random Forest classification
- Prediction confidence estimation
- Video annotation

---

## 💻 Features

- 🎥 Video Processing
- 👤 Person Detection
- 📊 Temporal Aggregation
- 🚶 Motion Analysis
- 🌳 Random Forest Classification
- 📈 Prediction Confidence
- 📹 Output Video Generation

---

## 🛠️ Technologies Used

- Python
- Kaggle Notebook
- YOLOv8
- OpenCV
- NumPy
- Pandas
- Scikit-learn
- Ultralytics

---

## 📁 Repository Structure

```
temporal-aggregation/
│
├── README.md
├── LICENSE
├── temporal_aggregation.ipynb
├── images/
├── docs/
└── requirements.txt
```

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/Lathika-319/temporal-aggregation.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open the notebook in Jupyter Notebook or Kaggle.

4. Run all cells.

---

## 📸 Project Outputs

- Person Detection
- Temporal Feature Extraction
- Activity Classification
- Annotated Output Video

---

## 🎥 Demo Video

Watch the project demonstration here:
https://drive.google.com/drive/folders/1LQjz9aKLgD09g5JnU5M1Hdq1oOMoGX3e?usp=sharing

---

## 🔗 Kaggle Notebook:

https://www.kaggle.com/code/abhishekmanjunath18/temporal-aggregation

---

## 🚀 Future Enhancements

- Improve detection accuracy
- Support multiple object tracking
- Real-time CCTV monitoring
- Deploy as a web application
- Use deep learning-based temporal models

---

## 👩‍💻 Author

**Lathika S**

B.E. Computer Science and Engineering

UpToSkills Virtual Internship Project
