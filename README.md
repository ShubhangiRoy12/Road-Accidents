🚧 Smart Road Crack Detection using Image Processing
📌 Introduction

This project focuses on detecting cracks in road surface images using classical image processing techniques instead of deep learning. It is built using Python and OpenCV as part of a university Computer Vision project.

The goal is to assist authorities in quickly identifying damaged roads and prioritizing maintenance and repairs.

❗ Problem Statement

India has a vast road network of approximately 6.4 million kilometers, but many roads suffer from poor maintenance.

Road cracks can lead to:

Accidents
Vehicle damage
Water seepage and flooding
Increased long-term repair costs

Manual inspection is:

Time-consuming
Expensive
Inconsistent

➡️ Hence, an automated crack detection system is highly beneficial.

⚙️ Key Features
Load and process a single image or a folder of images
Convert images to grayscale
Reduce noise using Gaussian Blur
Enhance contrast using CLAHE
Detect edges using Canny Edge Detection
Apply adaptive thresholding
Perform morphological operations (dilation & erosion)
Detect and filter crack contours
Highlight cracks in red on original image
Classify crack severity (Low / Medium / High)
Display all intermediate processing stages
🛠️ Technology Stack
Python 3.8+
OpenCV (cv2)
NumPy
Matplotlib
📂 Project Structure
road-crack-detection/
├── data/
├── src/
├── outputs/
├── requirements.txt
├── PROJECT_REPORT.md
└── README.md
🚀 Installation Steps
Clone the repository
Create a virtual environment
Activate the environment

Install dependencies:

pip install -r requirements.txt
▶️ How to Run

Process all images in the data folder:

python src/main.py

Process a specific image:

python src/main.py data/sample1.jpg
🔍 Crack Detection Pipeline
Grayscale Conversion
CLAHE Contrast Enhancement
Gaussian Blur
Morphological Operations
Contour Detection
Crack Highlighting
Severity Estimation
📊 Severity Classification
Low → Crack area < 1%
Medium → Crack area between 1% and 5%
High → Crack area > 5%
🔮 Future Improvements
CNN-based deep learning models
Web-based interface
GPS tagging of detected cracks
Drone-based road inspection
Mobile app integration
👩‍💻 Author

Shubhangi Roy
VIT Bhopal University
Winter Semester 2025–2026
Computer Vision Project
