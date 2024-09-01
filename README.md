**Air Canvas**
**Overview**
Air Canvas is a Python-based application that allows users to draw on a virtual canvas using their fingers as a brush, detected by a webcam. This project leverages OpenCV for image processing and Mediapipe for hand landmark detection.

**Features**
Hand Gesture Recognition: Detects hand movements using Mediapipe and tracks the forefinger for drawing.
Color Selection: Switch between different colors (Blue, Green, Red, Yellow) by hovering over the color buttons on the screen.
Clear Canvas: Clear the drawing by hovering over the "CLEAR" button.
Real-Time Drawing: Draw in real-time on a virtual canvas that is displayed on your screen.

**Requirements**
Python 3.x
OpenCV
NumPy
Mediapipe

**Installation**
To install the necessary packages, run the following command:
pip install opencv-python numpy mediapipe

**Usage**
**Run the Script:**
Start the application by running the Python script:

python AIRPAINT.py

**Using the Canvas:**
Move your hand in front of the webcam. The application will detect your forefinger and allow you to draw on the canvas.
To change the color, move your forefinger over the color buttons displayed on the screen.
To clear the canvas, move your forefinger over the "CLEAR" button.

**Exit the Application:**
Press the 'q' key to exit the application.

**How It Works**
The application captures video from the webcam and processes each frame to detect the position of the user's forefinger.
Depending on the position of the forefinger, the application either draws on the canvas, changes the color, or clears the canvas.
Future Improvements
Brush Size Control: Implement a feature to change the brush size dynamically using gestures.
Save Functionality: Add an option to save the current canvas as an image.
Additional Tools: Introduce more tools such as an eraser or different brush shapes.

**Acknowledgments**
OpenCV
Mediapipe

**License**
This project is licensed under the MIT License. See the LICENSE file for details.
