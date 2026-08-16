\# Camera Calibration and Object Measurement



This project uses OpenCV for camera calibration and real-world object measurement.



\## Features



\- Camera calibration using a chessboard pattern.

\- Calculation of camera intrinsic parameters.

\- Distortion correction (Undistortion).

\- Object detection using contours.

\- Real-time estimation of object width and height in centimeters.



\## Technologies Used



\- Python

\- OpenCV

\- NumPy



\## Project Structure



\- camera\_calibration.py : Calibrates the camera and calculates the camera matrix.

\- object\_measurement.py : Measures object dimensions using the calibrated camera.

\- common.py : Helper functions used by the project.



\## Requirements



```bash

pip install -r requirements.txt

```



\## Run



\### Camera Calibration



```bash

python camera\_calibration.py

```



\### Object Measurement



```bash

python object\_measurement.py

```



\## Author



Ahmed Sherkawy

