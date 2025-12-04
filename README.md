# Air-Canvas-Hand-Gesture-Based-Virtual-Drawing-Application
Air Canvas is a hand-gesture based virtual drawing application built using Python, OpenCV, and MediaPipe. It tracks fingertip movements in real time to draw on the screen, with features like color selection, eraser mode, and clear-screen gestures for an interactive drawing experience.
Algorithm
Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)

Prepare the canvas frame and put the respective ink buttons on it.

Adjust the values of teh mediapipe intilization to detect one hand only.

Detect teh landmarks by passing the RGB frame to the mediapipe hand detector

Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)

Finally draw the points stored in array on the frames and canvas .

Requirements: python3 , numpy , opencv, mediapipe installed on your system.
