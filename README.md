# Vehicle-Proximity-Alert

Vehicle-Proximity-Alert is a real-time proximity alert system that detects vehicles and other objects around your car using computer vision. It uses the YOLOv4-tiny object detection model to detect cars, bicycles, motorbikes, and persons in a video feed and raises an alert if any of these objects are too close to your car. This system can help enhance driving safety by alerting drivers about potential hazards around them.

# Features

- Real-time object detection using YOLOv4-tiny
- Detects cars, bicycles, motorbikes, and persons
- Displays a visual warning when objects are too close
- Plays an audio alert when objects are in high proximity
- Works with video input (e.g., a dashcam)

# Prerequisites

- Python 3.6 or higher
- OpenCV
- Numpy
- Beepy

# Installation

Clone the repository: <bash git clone https://github.com/HumaidIlyas/Vehicle-Proximity-Alert.git>

Install the required dependencies: pip install opencv-python opencv-python-headless numpy beepy

# Usage

Place your video file in the project directory and replace the video = cv2.VideoCapture('Your_Video_File.mp4') line in the code with the name of your video file.
Run the script: python proximity_alert.py
The script will process the video and display a window with the detected objects and proximity alerts.
Press q to quit the video.

# Contribute

Feel free to open issues or submit pull requests to contribute to the project. We appreciate your help in improving Vehicle-Proximity-Alert!

# License

Vehicle-Proximity-Alert is released under the MIT License. See LICENSE for more information.
