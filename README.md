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

- Clone the repository: `bash git clone https://github.com/HumaidIlyas/Vehicle-Proximity-Alert.git`

- Install the required dependencies: `pip install opencv-python opencv-python-headless numpy beepy`

# Usage

- Place your video file in the project directory and replace the `video = cv2.VideoCapture('Your_Video_File.mp4')` line in the code with the name of your     video file.
- Run the script: `python proximity_alert.py`
- The script will process the video and display a window with the detected objects and proximity alerts.
- Press q to quit the video.

# Usage with Webcam
  You can also use this project with a webcam, including your mobile phone's camera mounted on your car dashboard. One way to achieve this is by using a     third-party app like "Iriun Webcam."
  
## Setting up Iriun Webcam

### Download and install the "Iriun Webcam" app on your mobile phone:
- [Android](https://play.google.com/store/apps/details?id=com.jacksoftw.webcam&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1)
- [iOS](https://apps.apple.com/us/app/iriun-webcam/id1468908191)

### Install the Iriun Webcam software on your computer:
- [Windows](https://1758658189.rsc.cdn77.org/IriunWebcam-2.7.8.exe)
- [macOS](https://1758658189.rsc.cdn77.org/IriunWebcam-2.8.3.pkg)
- [Ubuntu](https://iriun.gitlab.io/iriunwebcam-2.8.deb)

## Connect your mobile phone and computer to the same Wi-Fi network.
- Launch the Iriun Webcam app on your mobile phone and start the Iriun Webcam software on your computer. Your computer should automatically detect your       mobile phone's camera as a webcam.
- Running the Proximity Alert System with Webcam
- To use the script with your webcam or Iriun Webcam, follow these steps:
  In the script, replace the line: `video = cv2.VideoCapture('Beat_white.mp4')`
  with:
  `video = cv2.VideoCapture(0)`
- Change the index 0 to the appropriate index of your webcam if necessary (e.g., 1, 2, etc.).
- To stop outputting the video, comment out or remove the following line: `output_video.write(frame)`
- Run the script, and the Proximity Alert System should work with your webcam or mobile phone camera mounted on your car dashboard.
- Remember that the performance of the system may depend on the quality of your mobile phone camera, the clarity of the video feed, and the stability of     the Wi-Fi connection between your phone and computer.

![WhatsApp Image 2023-04-16 at 16 24 31](https://user-images.githubusercontent.com/40148304/232302652-93e8e6a6-3dff-48c2-aa68-b3b545c2549a.jpeg)

![WhatsApp Image 2023-04-16 at 16 26 18](https://user-images.githubusercontent.com/40148304/232302675-a998c8c2-4474-45dd-9871-6cf2988eb530.jpeg)


# Contribute

Feel free to open issues or submit pull requests to contribute to the project. We appreciate your help in improving Vehicle-Proximity-Alert!

# License

Vehicle-Proximity-Alert is released under the MIT License. See LICENSE for more information.
