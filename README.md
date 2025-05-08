# Real-Time Object Detection using YOLOv8 and OpenCV

This project demonstrates real-time object detection using the YOLOv8 model from the Ultralytics library with OpenCV to display live results from a webcam.

## 📸 Features

- Real-time object detection using your webcam.
- YOLOv8 (Small model - `yolov8s.pt`) for fast and accurate results.
- Tracks and labels detected objects with different colors.
- Displays confidence score for each detection.

## 🛠️ Requirements

- Python 3.8 or higher
- Ultralytics YOLO
- OpenCV

Install the dependencies with:

```bash
pip install -r requirements.txt

🚀 How to Run
Clone this repository:
git clone https://github.com/dishapawarkhausi/object-detection-yolov8.git
cd object-detection-yolov8

Run the Python script:
python object_detection.py
Press q to quit the webcam stream.

📦 Files
object_detection.py: Main Python script.
requirements.txt: Python dependencies.
README.md: Project documentation.

🧠 Model Info
This project uses the YOLOv8 small model (yolov8s.pt) provided by Ultralytics. You can use other variants like yolov8n.pt, yolov8m.pt, etc., depending on your accuracy/speed trade-off.

📌 Notes
Ensure your webcam is working.

The script uses a confidence threshold of 0.4 to filter detections.

✨ Credits
Ultralytics YOLO
OpenCV

Happy detecting! 😄
