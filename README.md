This project is a Python application that records the user's full screen along with a webcam overlay. The screen capture is saved as a .mp4 video file using OpenCV. The recording starts immediately and continues until the user presses the 'q' key to stop. Each recording is timestamped for unique file naming.

Language Used:
Python

Libraries Used:
- PIL (ImageGrab for screen capture)
- numpy (for handling image data)
- cv2 / OpenCV (for video recording, webcam feed, and saving output)
- pywin32 (GetSystemMetrics from win32api to fetch screen resolution)

Note:
- This application is intended for Windows systems.
- Webcam index `1` is used; adjust to `0` if needed for your default camera.
- Output video is saved in the current directory with a timestamp as the filename.
- Press the **'q'** key to stop the recording and save the video.
