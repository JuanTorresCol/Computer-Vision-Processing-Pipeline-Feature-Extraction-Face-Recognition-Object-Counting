# Computer-Vision-Processing-Pipeline-Feature-Extraction-Face-Recognition-Object-Counting

Repository containing a series of computer vision practices and solutions using OpenCV and Python. This project covers everything from classical feature extraction and facial detection techniques to morphological processing for automated object counting.

🛠️ Technologies and Libraries Used
Python

OpenCV (cv2) (opencv-contrib-python-headless)

NumPy

Matplotlib

Google Colab (compatible with local or cloud runtimes)

📂 Project Structure and Content
1. Feature Extraction (Part 1)
Implementation and visual comparison of key algorithms for interest point and descriptor detection:

SIFT (Scale-Invariant Feature Transform): Scale and rotation-invariant feature detection.

FAST (Features from Accelerated Segment Test): High-speed corner detection with and without non-max suppression.

ORB (Oriented FAST and Rotated BRIEF): Efficient oriented alternative.

Feature Matching: Matching descriptors using the Brute Force Matcher (BFMatcher).

2. Face and Eye Recognition (Part 2)
Face and eye detection in static images using Haar Cascade classifiers (haarcascade_frontalface_default.xml and haarcascade_eye.xml).

Integration of JavaScript snippets to capture and process frames in real-time using the webcam in Google Colab.

3. Segmentation and Object Counting (Part 3)
Image processing pipeline for automatic detection and counting of items (e.g., apples) based on:

Color space conversion from BGR to HSV.

Thresholding (cv2.inRange).

Morphological operations (Opening and Closing) for noise reduction and precise segmentation.

Contours (cv2.findContours) and bounding boxes (cv2.boundingRect).

🚀 Installation and Execution Guide
Clone this repository or open the scripts in Google Colab.

Make sure to install the required dependencies by running:

Bash
pip install opencv-contrib-python-headless
Run the code blocks corresponding to each section, ensuring you include the necessary resource files (test images and Haar classifiers in the root directory).
