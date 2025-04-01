# Pothole Detection Using YOLOv8

# Overview
This project aims to detect potholes in real-time using the **YOLOv8 Nano** model. Additional features include **Google Maps integration** to mark detected potholes and **data logging** for further analysis.

## Features
- **Real-time detection** using YOLOv8 Nano
- **Google Maps integration** using `folium`
- **Data logging** to store detected pothole locations
- **Efficient annotation** using Roboflow
- **Version control** using Git

## Tools Used
- **Python** – Primary programming language
- **YOLOv8 Nano** – Lightweight object detection model
- **OpenCV** – Image processing and real-time video analysis
- **Folium** – Google Maps integration for pothole location tracking
- **Git** – Version control for code management
- **Roboflow** – Used for dataset annotation and preprocessing

## Directory Structure
```
Pothole-Detection/
│-- dataset/            # Contains training dataset
│-- scripts/               # Python scripts for model training and detection
│-- output/             # Stores detected pothole images and logs
│-- README.md           # Project documentation
│-- requirements.txt    # Dependencies 
```
## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/csshashanksharma/Pothole-Detection.git
   cd Pothole-Detection
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the pothole detection script:
   ```bash
   python traainYolov82.ipynb
   ```

## Usage
- Ensure your webcam is connected (if using real-time detection)
- Run the script and observe pothole detections on the video stream
- The detected pothole locations will be plotted on a map using `folium`

## Contributing
Feel free to submit **issues** or **pull requests** for improvements!
