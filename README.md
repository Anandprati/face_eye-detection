# face_eye-detection

This project demonstrates the implementation of face and eye detection using the OpenCV library. The application utilizes the Haar feature-based cascade classifiers to detect faces and eyes in images or real-time video streams.

**Requirements**

To run this project, you need to have the following:

Python 3.x
OpenCV library (install using pip install opencv-python)
Haar cascade files for face and eye detection (provided in the repository)

# Usage

**Image Detection**

To detect faces and eyes in an image, run the following command:

python detect_image.py --image path/to/image.jpg
Replace path/to/image.jpg with the path to your desired image file.

**Video Detection**

To detect faces and eyes in real-time video, run the following command:

bash
Copy code
python detect_video.py
A new window will open displaying the video feed from your webcam, and rectangles will be drawn around detected faces and eyes.

Press Q to quit the application.

# Customization

You can customize the behavior of the detection algorithm by modifying the following parameters in the code:

SCALE_FACTOR: Specifies how much the image size is reduced at each image scale.
MIN_NEIGHBORS: Specifies how many neighbors each candidate rectangle should have to retain it.
MIN_SIZE: Minimum possible object size. Objects smaller than this are ignored.
DETECTION_COLOR: Color of the rectangles drawn around the detected faces and eyes.
Feel free to experiment with different values to achieve the desired results.

# Credits

This project is inspired by the OpenCV library and utilizes its Haar cascade classifiers for face and eye detection. The Haar cascade files are part of the official OpenCV repository.

**OpenCV: https://opencv.org**
