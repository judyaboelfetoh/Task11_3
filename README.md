# Task11_3
# Description of the process
First thing I converted the image to gray scale in order to be easier in edge detection and contour analysis, then I used gaussian blurring to smoothen the image.
Second, I used Canny for edge detection, then I did contouring to detect the shapes.
Regarding the color detection, I made a dictionary that contains each color as a key and their upper and lower cases as a 2D array value. I converted to hsv and I masked the image.
The shapes were contoured and everything was great, but there is a problem in the color detection.
