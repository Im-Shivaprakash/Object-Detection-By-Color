# Object Detection using OpenCV

This project focuses on real-time object detection using OpenCV, a popular computer vision library in Python. The objective is to detect and track objects of interest from a live video stream captured by a webcam.

## Overview

Object detection is a crucial task in computer vision with applications in various domains such as surveillance, security, and automation. This project utilizes OpenCV to perform object detection in real-time, specifically focusing on detecting objects of a certain color range.

## Key Features

- **Color-based Detection**: The project detects objects based on their color range, allowing for flexible object selection.
- **Real-time Tracking**: Objects are tracked and their movements are monitored in real-time from a live video feed.
- **Simple User Interface**: The application provides a simple and intuitive interface for object detection and tracking.

## Usage

1. **Color Range Configuration**: Adjust the lower and upper HSV (Hue, Saturation, Value) thresholds to define the color range of the object to be detected.
2. **Object Detection**: Run the script to initiate object detection from the live video feed captured by the webcam.
3. **Real-time Tracking**: The script will track and display the detected object's movements in real-time.
4. **Interaction**: Interact with the detected object by performing specific actions based on its position and size.

## Dependencies

- OpenCV
- PyAutoGUI
- Imutils

## File Structure

- `object_detection.py`: Python script containing the code for object detection and tracking.
  
## Contributions

Contributions to this project are welcome! Whether it's bug fixes, enhancements, or new features, feel free to open issues or submit pull requests to improve the functionality and performance of this object detection project.

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for detailed terms and conditions.
