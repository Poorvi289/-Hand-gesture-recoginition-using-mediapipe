# -Hand-gesture-recoginition-using-mediapipe

Estimate hand pose using MediaPipe (Python version).
This is a sample program that recognizes hand signs and finger gestures with a simple MLP using the detected key points.
❗ ️This is English Translated version of the original repo. All Content is translated to english along with comments and notebooks ❗

This repository contains the following contents.

Sample program
Hand sign recognition model(TFLite)
Finger gesture recognition model(TFLite)
Learning data for hand sign recognition and notebook for learning
Learning data for finger gesture recognition and notebook for learning

<img width="1195" height="715" alt="Screenshot 2024-12-20 112543" src="https://github.com/user-attachments/assets/e4bf301a-2c3d-4031-90f9-e9d005f0a8c7" />
<img width="1195" height="718" alt="Screenshot 2024-12-20 112501" src="https://github.com/user-attachments/assets/fba796c3-26d1-4be3-adb5-06e8d14dda3a" />


Requirements:
:mediapipe 0.8.1
:OpenCV 3.4.2 or Later
:Tensorflow 2.3.0 or Later
:tf-nightly 2.5.0.dev or later (Only when creating a TFLite for an LSTM model)
:scikit-learn 0.23.2 or Later (Only if you want to display the confusion matrix)
:matplotlib 3.3.2 or Later (Only if you want to display the confusion matrix)

Demo:
Here's how to run the demo using your webcam.

python app.py
The following options can be specified when running the demo.

--device
Specifying the camera device number (Default：0)
--width
Width at the time of camera capture (Default：960)
--height
Height at the time of camera capture (Default：540)
--use_static_image_mode
Whether to use static_image_mode option for MediaPipe inference (Default：Unspecified)
--min_detection_confidence
Detection confidence threshold (Default：0.5)
--min_tracking_confidence
Tracking confidence threshold (Default：0.5)90

Reference:
https://mediapipe.dev/



