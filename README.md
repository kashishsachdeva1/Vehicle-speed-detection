# Real-Time Vehicle Speed Detection using YOLOv8

## Overview
This project implements real-time vehicle speed estimation using YOLOv8 and OpenCV. It identifies moving vehicles in a video, tracks their movement across frames, and calculates their speed based on the time taken to cross predefined boundaries.

## Features
- Vehicle detection using YOLOv8
- Speed estimation based on object tracking
- Red and blue boundary lines for speed calculation
- Frame-by-frame visualization with speed annotations
- Stores detected frames for further analysis

## Installation
1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd Speed-detection-of-vehicles
   ```
2. Install dependencies:
   ```sh
   pip install ultralytics opencv-python numpy pandas joblib
   ```
3. Ensure you have YOLOv8 weights (`yolov8s.pt`) and a video file (`highway_mini.mp4`).

## Usage
Run the script to process the video and estimate vehicle speeds:
```sh
python speed_detection.py
```

## Output
- Annotated video (`output.avi`) with speed measurements
- Detected frames stored in `detected_frames/`

## Dependencies
- Python 3.x
- OpenCV
- Ultralytics YOLOv8
- NumPy, Pandas, Joblib

## License
This project is open-source under the MIT License.

## Author
[Kashish Sachdeva](https://github.com/kashishsachdeva1)

