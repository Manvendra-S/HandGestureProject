# HandGestureProject

This Python script utilizes OpenCV to perform real-time hand gesture recognition using a webcam feed. It detects hand gestures based on color thresholding and contour analysis techniques and maps these gestures to specific keyboard actions.

## Features:
- Color thresholding and contour analysis for hand gesture detection.
- Mapping of hand gestures to keyboard actions such as play/pause, volume control, and navigation.
- Adjustable color threshold parameters via trackbars for fine-tuning.

## Requirements:
- Python 3.x
- OpenCV (cv2)
- NumPy
- PyAutoGUI
- Time

## How to Run:
1. Ensure Python 3.x is installed on your system.
2. Install the required Python libraries using the following command:
    ```
    pip install -r requirements.txt
    ```
3. Run the `main.py` script by executing the following command:
    ```
    python main.py
    ```
4. Adjust the color threshold parameters using the trackbars in the "Color Adjustments" window.
5. Perform hand gestures in front of the webcam to control keyboard actions.

## Setting Color Threshold Parameters:
- After running the script, a window titled "Color Adjustments" will appear.
- Use the trackbars to adjust the following color threshold parameters:
  - `Lower_H`, `Lower_S`, `Lower_V`: Lower bounds for the HSV color space.
  - `Upper_H`, `Upper_S`, `Upper_V`: Upper bounds for the HSV color space.
  - `Thresh`: Threshold value for additional filtering (binary thresholding).

## File Descriptions:
- `main.py`: The main Python script for hand gesture recognition.
- `README.md`: This file, providing an overview of the project, instructions for usage, and setting color parameters.
- `requirements.txt`: A list of required Python libraries and their versions.

