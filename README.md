# opencv-face-regcognition-python
This project demonstrates a basic face recognition system using Python and OpenCV. It captures real-time video from a webcam, detects faces, and recognizes them using the Local Binary Patterns Histograms (LBPH) algorithm.
Codez Up
+1
{app_name}/
+1
GitHub

Features
Real-time face detection and recognition using a webcam.

Utilizes OpenCV's LBPH face recognizer for accurate recognition.

Displays recognized faces with labels on the video feed.

Includes a sample output image (output.png) showcasing the recognition result.
GitHub

Prerequisites
Ensure you have the following installed:

Python 3.x

OpenCV

NumPy

You can install the required packages using pip:

bash
Copy
Edit
pip install opencv-python numpy
Getting Started
Clone the repository:

bash
Copy
Edit
git clone https://github.com/solo-king-18/opencv-face-regcognition-python.git
cd opencv-face-regcognition-python
Prepare the training data:

Organize your training images in a directory structure as follows:

kotlin
Copy
Edit
training-data/
├── s1/
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ...
├── s2/
│   ├── 1.jpg
│   ├── 2.jpg
│   └── ...
Each subdirectory (s1, s2, ...) represents a different person, and the images inside are used for training the recognizer.

Run the face recognition script:

bash
Copy
Edit
python OpenCV-Face-Recognition-Python.py
The script will open a window displaying the video feed from your webcam with detected faces labeled accordingly.

Files in the Repository
OpenCV-Face-Recognition-Python.py: Main script for face detection and recognition.

OpenCV-Face-Recognition-Python.ipynb: Jupyter Notebook version of the main script for interactive exploration.

output.png: Sample output image showing the recognition result.

README.md: This readme file.

Acknowledgments
This project is inspired by various OpenCV face recognition tutorials and serves as a foundational implementation for learning purposes.

Author
J J Jefrin
