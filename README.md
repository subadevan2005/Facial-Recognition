# Facial Recognition using Haar Cascade Classifier
This project implements real-time facial recognition using Python and OpenCV with the Haar Cascade classifier. It detects faces in a video stream from the default camera, draws rectangles around them, and displays the processed video.

## Getting Started
### Prerequisites
Python 3.x
OpenCV (pip install opencv-python)

### Clone Repository
git clone https://github.com/subadevan2005/Facial-Recognition.git
cd Facial-Recognition

### Download Haar Cascade Classifier
Download the Haar Cascade XML file for face detection:
haarcascade_frontalface_default.xml
Place it in the same directory as your Python script (facial_recognition.py).

### Usage
Run the facial recognition script:

#### python facial_recognition.py


### Instructions
#### Face Detection:
Uses a pre-trained Haar Cascade classifier (haarcascade_frontalface_default.xml) for face detection.

#### Video Capture:
Captures video frames from the default camera (index 0).

#### Face Recognition:
Converts each frame to grayscale and detects faces using CascadeClassifier.detectMultiScale().
Draws rectangles around detected faces (cv2.rectangle()).

#### Display:
Displays the processed video with rectangles around detected faces using cv2.imshow().

#### Quit:
Press 'q' to exit the application (cv2.waitKey()).
Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request for any improvements or bug fixes.

### Acknowledgments
This project utilizes the OpenCV library for computer vision tasks.
Special thanks to the OpenCV community for maintaining the Haar Cascade classifiers.
