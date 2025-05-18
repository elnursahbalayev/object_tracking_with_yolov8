# Object Tracking with YOLOv8

## Description
This project implements real-time object tracking using YOLOv8, a state-of-the-art object detection and tracking model. The application processes video input, detects objects, and tracks them across frames.

## Features
- Real-time object detection and tracking
- Support for video file processing
- Persistent tracking of objects across frames
- Visual display of tracking results

## Dependencies
- Python 3.x
- OpenCV (cv2)
- Ultralytics YOLOv8
- Other dependencies as required by YOLOv8

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/object_tracking_with_yolov8.git
cd object_tracking_with_yolov8
```

2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows, use: .venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install ultralytics opencv-python
```

4. Download the YOLOv8 model (if not included in the repository):
```bash
# The model will be downloaded automatically when first running the script
# or you can manually place the yolov8n.pt file in the project directory
```

## Usage

1. Place your video file in the project directory or update the `video_path` variable in `main.py` to point to your video file.

2. Run the main script:
```bash
python main.py
```

3. Press 'q' to exit the application.

## Customization

You can modify the `main.py` file to:
- Use different YOLOv8 models (e.g., yolov8s.pt, yolov8m.pt, etc.)
- Process different video sources (files, webcams, RTSP streams)
- Adjust tracking parameters
- Implement additional features

## License
[Specify your license here]

## Acknowledgements
- [Ultralytics](https://github.com/ultralytics/ultralytics) for the YOLOv8 implementation
