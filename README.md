# 🛣️ Smart Road Crack Detection using Image Processing

A computer vision project that detects cracks in road surface images using **classical image processing techniques** — no deep learning required. Built with Python and OpenCV as a university course project.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-green?logo=opencv)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Problem Statement

India has one of the largest road networks in the world (~6.4 million km), yet a significant portion suffers from poor maintenance. Cracked roads lead to:

- **Accidents** — especially for two-wheelers and cyclists  
- **Vehicle damage** — tyres, suspension, and alignment issues  
- **Higher maintenance costs** due to delayed repairs  
- **Flooding** — cracks allow water seepage, weakening the road  

Manual inspection is **slow, expensive, and inconsistent**.  
An automated image-based crack detection system can help authorities quickly identify damaged roads and prioritize repairs.

---

## ✨ Features

| # | Feature | Description |
|---|---------|-------------|
| 1 | **Image Loading** | Load single image or batch-process folder |
| 2 | **Grayscale Conversion** | Simplifies image processing |
| 3 | **Noise Removal** | Gaussian Blur |
| 4 | **Contrast Enhancement** | CLAHE |
| 5 | **Edge Detection** | Canny Edge Detection |
| 6 | **Thresholding** | Adaptive thresholding |
| 7 | **Morphological Ops** | Dilation & Erosion |
| 8 | **Contour Detection** | Identify crack regions |
| 9 | **Crack Highlighting** | Red overlay on original image |
| 10 | **Severity Classification** | Low / Medium / High |
| 11 | **Pipeline Visualization** | Shows all stages |

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Python 3.8+ |
| Computer Vision | OpenCV (`cv2`) |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |

---

## 📁 Folder Structure

```

road-crack-detection/
├── data/
├── src/
├── outputs/
├── requirements.txt
├── PROJECT_REPORT.md
└── README.md

````

---

## 🚀 Installation

### Prerequisites
- Python 3.8+
- pip

### Steps

1. Clone the repository
```bash
git clone [https://[ShubhangiRoy12/your-username/road-crack-detection.git](https://github.com/ShubhangiRoy12/Road-Accidents/)]
cd road-crack-detection
````

2. Create virtual environment

```bash
python -m venv venv
```

3. Activate environment

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

### Run on all images

```bash
python src/main.py
```

### Run on single image

```bash
python src/main.py data/sample1.jpg
```

---

## 🔍 Crack Detection Pipeline

1. Grayscale Conversion
2. CLAHE Contrast Enhancement
3. Gaussian Blur
4. Morphological Operations
5. Contour Detection
6. Crack Highlighting
7. Severity Estimation

---

## 📊 Severity Classification

| Level     | Crack Area | Meaning         |
| --------- | ---------- | --------------- |
| 🟢 LOW    | < 1%       | Minor cracks    |
| 🟡 MEDIUM | 1% – 5%    | Moderate damage |
| 🔴 HIGH   | > 5%       | Severe damage   |

---

## 🧠 How It Works

```
Input Image
   ↓
Grayscale
   ↓
CLAHE
   ↓
Gaussian Blur
   ↓
Edge Detection + Thresholding
   ↓
Morphological Operations
   ↓
Contour Detection
   ↓
Crack Highlight + Severity
```

---

## 🔮 Future Improvements

* Deep Learning (CNN-based detection)
* Web Interface
* GPS Tagging
* Drone-based monitoring
* Mobile App

---

## 📝 License

This project is for educational purposes.

---

## 👩‍💻 Author

**Shubhangi Roy**
VIT Bhopal University
Winter Semester 2025–2026
Computer Vision Project

```

