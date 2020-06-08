# SettingUpWebcam
In the times of corona having a good webcam is quite beneficial. Alas, standard webcams became quite expensive, hence the decision towards using an OEM webcam.
The problem hereby is that an OEM webcam lacks a suiteable casing to mount on a webcam as well as a calibration. This repository therefore documents my solution to this problem.

Insert picture final solution.

## Structure

3D Modell folder contains the CAD model which allows flexible mounting 

CalibrationImages includes the pictures used for calibration (delete and put new calibration images here)



## External Dependencies

* Ubuntu 18.x
* OpenCV 4.1x 
* pyfakeWebcam
* numpy


## How to Use

Take pictures with the webcam of a chess board (change the number) and add them to the calibration images (delete the current ones). Run "python3 calibrateCamera.py"

To Use adjust the incoming and outgoign videostream in fakeWebcam.py . Run "python3 fakewebcam.py"

