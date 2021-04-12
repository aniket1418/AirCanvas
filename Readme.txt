# Air-Canvas-project
Computer vision project implemented with OpenCV
Ever wanted to draw your imagination by just waiving your finger in air.
In this I am trying to build an Air Canvas which can draw anything on it
by just capturing the motion of a coloured marker with camera.
Technology is used to build the project is computer vision and OpenCV
and Language is Python 

# Algorithm

1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it.
3.. Adjust the trackbar values for finding the mask of coloured marker.
4. Preprocess the mask with morphological operations.(Erotion and dilation)
5. Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
6. Finally draw the points stored in array on the frames and canvas .



Requirements: python3 , numpy , opencv installed on your system.