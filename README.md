# Feature-Based Traffic Monitoring System

This project demonstrates basic traffic monitoring using classical Computer Vision techniques.

The system detects edges, represents objects using contours, and extracts important image features useful for intelligent transportation systems.

## What This Project Does

- Detects edges using Sobel and Canny operators
- Identifies vehicles and road objects using contours
- Computes object area and perimeter
- Extracts keypoints using ORB feature detector
- Visual comparison of different techniques

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

## How to Run

Install dependencies:

pip install opencv-python numpy matplotlib

Run:

python traffic_monitoring.py

## Output

The program saves results inside the **outputs/** folder:

- Original image
- Sobel edges
- Canny edges
- Contours with bounding boxes
- ORB feature visualization
- Final comparison figure

## Real World Use

Feature extraction helps traffic systems in:
- Vehicle detection
- Object tracking
- Traffic monitoring
- Smart transportation analysis

## Academic Note

This project is developed individually for the Image Processing & Computer Vision course.
External documentation was used only for learning reference.
