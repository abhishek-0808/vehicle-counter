# Vehicle Detection and Counting System
This project implements a real-time vehicle detection and counting system using OpenCV in Python. It detects vehicles in a video stream, counts them as they cross a predefined line, and displays the count on the screen.

## Features
- Detects vehicles in a video stream.
- Counts vehicles as they cross a designated line.
- Displays the count of vehicles on the screen.
- Uses background subtraction and contour detection for vehicle detection.
- Simple interface with clear visualizations.
## Requirements
Python 3.x
OpenCV
NumPy
## Configuration
- video.mp4: Replace this with the path to your video file. The system will detect vehicles in this video.
- min_width_rect and min_height_rect: Adjust these values to set the minimum width and height of detected vehicle rectangles.
- count_line_position: Modify this to change the position of the counting line on the video frame.
- offset: Set the offset value for line crossing detection.
