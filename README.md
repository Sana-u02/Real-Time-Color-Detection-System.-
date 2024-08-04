# Real-Time-Color-Detection-System.-
This code captures video from a webcam, analyzes the color at the center of each frame, and displays the color name in real-time. 

### Working

***1. Open Webcam:*** It tries to connect to the webcam by checking up to three possible video sources.

***2. Capture and Process Frames:***
- Continuously captures frames from the webcam.
- Converts the frame to HSV color space to get accurate color information.
- Determines the color of the pixel in the center of the frame.

***3. Display Color:***
- Shows the name of the detected color on the screen.
- Draws a circle at the center of the frame to highlight it.

***4. Exit:*** Closes the video feed and windows when the "ESC" key is pressed.

### Build With

**1.Python:** The programming language used.

**2. OpenCV (cv2):** A library for computer vision tasks, used here for video capture, image processing, and display.

**3. NumPy:** A library for numerical operations (though not explicitly used in this snippet, it’s often used with OpenCV).
