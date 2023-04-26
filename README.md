# Face detection and plot
This program is a face detection model. It learns and predicts facial expressions. It is a classification task that visualizes the estimated probability for each class. The program is in Jupyter notebook format and has only been tested on Ubuntu 22.04 LTS because Mediapipe couldn't be installed properly on Windows for some reason.
# Environment and Install packages (anaconda) 
 - `conda create --name fd python=3.7`
 - `pip install -r requirements.txt`
 - `connect camera and  cap = cv2.VideoCapture("cameraID or video path")`  